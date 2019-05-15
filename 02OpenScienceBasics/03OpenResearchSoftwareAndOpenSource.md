<img src="/Images/Icons/open_source_software.png" width="150" height="150" /> <img src="/Images/Icons/publish.png" width="150" height="150" />
## 3. Open Research Software and Open Source

### What is it?

Open research software, or open-source research software, refers to the use and development of software for analysis, simulation, visualization, etc. where the full source code is available. In addition, according to the [Open Source Definition](https://opensource.org/osd), open-source software must be distributed in source and/or compiled form \(with the source code available in the latter case\), and must be shared under a license that allows modification, derivation, and redistribution.

### Rationale

Modern research relies on software, and building upon—or reproducing—that research requires access to the full source code behind that software \([Barnes, 2010](https://doi.org/10/cj8t6n); [Morin et al., 2012](https://doi.org/10/m5t); [Ince et al., 2012](https://doi.org/10/hqg); [Prins et al. 2015](https://doi.org/10/f3mn4p); [Lowndes et al., 2018](https://doi.org/10/gc4jb3)\). As Buckheit and Donoho put it, paraphrasing Jon Claerbout, ‘‘An article about a computational result is advertising, not scholarship. The actual scholarship is the full software environment, code and data, that produced the result’’ \([Buckheit & Donoho, 1995](https://doi.org/10.1007/978-1-4612-2544-7_5)\). Open access to the source code of research software also helps improve the impact of the research \([Vandewalle, 2012](https://doi.org/10/gc5sjp)\).

Sharing software used for research \(whether computational in nature, or that relies on any software-based analysis/interpretation\) is a necessary, though not sufficient, condition for reproducibility. This is due to the unavoidable ambiguity that arises when trying to fully describe software using natural language, e.g., in a paper \([Ince et al., 2012](https://doi.org/10/hqg)\). Furthermore, many \(if not most\) software programs may contain some undetected errors \([Soergel, 2015](https://doi.org/10/gc5sjg)\), so even a "perfect" written description of software would not be able to account for all results.

In addition to reproducibility, sharing software openly allows developers to receive career credit for their efforts, either through direct citation \([Smith et al., 2016](https://doi.org/10/bw3g)\) or via software meta-articles published in, e.g., the [Journal of Open Research Software](http://openresearchsoftware.metajnl.com) or the [Journal of Open Source Software](http://joss.theoj.org) \([Smith et al., 2018](https://doi.org/10/gc5sjf)\). Neil Chue Hong maintains a [list of many domain-specific journals](https://www.software.ac.uk/which-journals-should-i-publish-my-software) that publish software articles.

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Learning objectives

1. Learn the characteristics of open software; understand the ethical, legal, economic, and research-impact arguments for and against open software, and further understand the quality requirements of open code.

2. Learn how to use existing open software and appropriately attribute \(cite\) it.

3. Learn how to use common tools and services for sharing research codes openly.

4. Be able to choose the appropriate license for their software, and understand the difference between permissive and non-permissive licenses.

### Key components

## <img src="/Images/Icons/brain.png" width="150" height="150" />
#### Knowledge

There are several different platforms that support open sharing and collaboration on software, research or otherwise. First of all, you can use this checklist to evaluate openness of existing research software:

* Is the software available to download and install?

* Can the software easily be installed on different platforms?

* Does the software have conditions on the use?

* Is the source code available for inspection?

* Is the full history of the source code available for inspection through a publicly available version history?

* Are the dependencies of the software \(hardware and software\) described properly? Do these dependencies require only a reasonably minimal amount of effort to obtain and use?

These qualities relate to and build on the [Open Source Definition](https://opensource.org/osd).

[Git](www.github.com) is a popular tool that allows version control: management and overall tracking of changes in a particular piece of software. Services such as [GitHub](https://github.com), [GitLab](https://about.gitlab.com/), [Bitbucket](https://bitbucket.org/), and others provide an interface to the tool as well as remote storage services that can be used to maintain, share, and collaborate on research software. As a tool it is quite widespread and, although it has an initial learning curve, it has proven invaluable to establishing an open and reproducible research workflow.

Having the research software on GitHub is just the first part; it is equally important to have a published and persistent identifier associated with it, such as a DOI. There are several ways of associating a DOI with a GitHub repository; the easiest one is to employ [Zenodo](https://zenodo.org/) \(a free, open catch-all repository created by [OpenAIRE](https://www.openaire.eu/) and [CERN](https://home.cern/)\) to do the assignment, although other repositories for archiving software and obtaining a DOI do exist, such as [Figshare](https://figshare.com/). [Zenodo integrates with GitHub](https://guides.github.com/activities/citable-code/) to archive the software and provide a DOI when developers make a formal release on GitHub.

Publicly shared software is not actually open source unless accompanied by a suitable license, because by default software \(along with any other creative work\) falls under exclusive copyright to the creators, meaning no one else can use, copy, distribute, or modify your work \([choosealicense.com](https://choosealicense.com/no-permission/)\). \(If you truly want to share your code with no restrictions whatsoever, you can [dedicate it to the public domain](https://choosealicense.com/licenses/#unlicense).\) Instead, you should choose an appropriate license for your software, based on what you would prefer to let others do \(or prevent them from doing\) with your code; the [choosealicense.org](https://choosealicense.com) site is a helpful resource to differentiate between licenses, although it does not feature [every available or popular open-source license](https://opensource.org/licenses). Once you select a license, put the text—edited to include the author name\(s\) and year—in the software repository as a plaintext LICENSE file.

![](/Images/02%20Open%20Science%20Basics/02_open_research_software_open_source.png)

Although sharing software in any form is better than not sharing it, your software will have more impact and be more easily used by others—and your future self!—if you include documentation. This can include helpful comments in the code that explain **why** you did something \(rather than what you did, which should be evident\), an informative README file that describes what your software does and gives some helpful information \(e.g., how to install, how to cite, how to run, important dependencies\), tutorials/examples, and/or API documentation \(which may be automatically generated from properly formatted comments in the code\).

Missing or inaccessible dependencies or insufficient documentation of the computational environment are very common barriers to reuse and reproducibility. One approach to address these barriers is to share your code with your computational environment using container technology. Containers package the code with the dependencies and computational environment so others can more easily run your analysis. Examples of container implementation in research include [Rocker](https://arxiv.org/abs/1710.03675), [Binder](https://mybinder.readthedocs.io/en/latest/), and [Code Ocean](https://codeocean.com/).

When you use software — whether you wrote it, or someone else did and made it available — appropriate citation is important for reproducibility \(discussed more in [Section 4](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md); briefly, the version used can change your results or interpretation\) and giving credit to the developers of the software \([Niemeyer 2016](doi.org/10/gc5sjd), [Smith 2016](https://doi.org/10/bw3g)\). The decision of when to cite software is up to you as the researcher, but we recommend a citation whenever the software did some work integral to your results, interpretation, or conclusions. The best way to make _your_ code easily citable is to use the GitHub–Zenodo integration described before and provide the resulting DOI in an obvious place like the software’s README, perhaps along with a suggested citation format. When citing any software, you should include at minimum the author name\(s\), software title, version number, and unique identifier/locator \([Smith 2016](https://doi.org/10/bw3g)\). If you use someone else’s software and they provided a DOI, then you can easily use that to identify and point to the software; if they did not archive their software, then you should include a URL where the software can be found and the version number or \(e.g.\) commit hash.

Additional, more complicated concepts include automated testing and continuous integration of software, packaging of software in binary formats, and governance and management of multi-person open-source projects \(i.e., codes of conduct, contributing guides\). Some of these topics are described by [Scopatz and Huff \(2015\)](http://lilith.fisica.ufmg.br/~dickman/transfers/comp/textos/Effective%20Computation%20in%20Physics%20(Python).pdf). [Wilson et al. \(2017\)](https://doi.org/10/gbkbwp) also provide a practical guide to best practices for scientific computing that includes advice specifically on research software development.

## <img src="/Images/Icons/laptop.png" width="150" height="150" />
##### Open Source Hardware

The open source principles above extend to hardware. Researchers often use proprietary instrumentation or hardware in their research that is not freely accessible, reusable, or adaptable. Scientific hardware includes everything from sequencing tools and microscopes to specialized testing equipment and particle colliders. Open Science Hardware \(OScH\) community, for example, is leading a push for the open source movement to include scientific tools, hardware, and research infrastructures through their [Global Open Science Hardware Roadmap](http://openhardware.science/global-open-science-hardware-roadmap/).

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Skills

* Create a repository on GitHub, and enable the integration with Zenodo. Mint the first release of the software.

* Choose a software license using \(e.g.\) [choosealicense](https://choosealicense.com) or the [Open Source Initiative](https://opensource.org/licenses).

* Create documentation for a software package, including README, comments, and examples.

* Appropriately cite software used for a paper.

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Questions, obstacles, and common misconceptions

Q: "I can’t share my software—it’s too messy / it doesn’t have good documentation / I didn’t leave good comments!"

A: Developers of research software around the world empathize with this feeling—people rarely feel like their code is "ready" to publicly share or that it is “finished”. However, as [Barnes \(2010\)](https://doi.org/10/cj8t6n) put it, “if your code is good enough to do the job, then it is good enough to release—and releasing it will help your research and your field.” In other words, if you feel comfortable enough with your software to publish a study or report results, then the code is sufficiently developed to share with your colleagues. \(In the other direction, if you don’t feel comfortable sharing the code, then perhaps it requires more development or testing before using in a publication\). Plus, sharing your code allows others to improve and build upon it, leading to even greater impact and innovation \(and citations for you!\).

Q: "What if someone takes the code I have shared and uses it for nefarious purposes, or claims they wrote it?"

A: Selecting an appropriate license for your software will help protect you from any uses of your software by others; for example, the common [MIT License](https://choosealicense.com/licenses/mit/) includes both limitations of liability and states that no warranty is provided. If someone else tries to claim that they wrote the software you made available, then you can point to the timestamps on your repository or archived versions as proof of your prior work.

Q: "If I share my code in an online repository, I will be deluged with requests for user support."

A: Although potential users may ask you for help, either via email or \(e.g.\) issues filed on the online repository, you are under no obligation to provide support if you prefer not to or cannot do so. An appropriate license even provides you with legal protection for this \(e.g., the no-warranty clause of the [MIT License](https://choosealicense.com/licenses/mit/)\).

Common misconception: simply putting code online makes it open-source software. In fact, unless the software is accompanied by a license that grants permission for others to use, copy, modify, and/or distribute, then the developer\(s\) retain exclusive copyright. A open-source license needs to accompany the code to make it open-source software.

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Learning outcomes

1. Be able to share software under the most appropriate license \(i.e., both the tools and the licensing\).

2. Be able to upload, version, and register a piece of code under a persistent identifier.

3. Be able to cite software used for a research article.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Further reading

* Balasegaram et al. (2017). An open source pharma roadmap. [doi.org/10.1371/journal.pmed.1002276](https://doi.org/10.1371/journal.pmed.1002276) 

* Dryden et al. (2017). Upon the Shoulders of Giants: Open-Source Hardware and Software in Analytical Chemistry. [doi.org/10.1021/acs.analchem.7b00485](https://pubs.acs.org/doi/abs/10.1021/acs.analchem.7b00485) 

* Ince et al. (2012). The case for open computer programs.[doi.org/10.1038/nature10836](https://doi.org/10.1038/nature10836)

* Iskoujina and Roberts (2015). Knowledge sharing in open source software communities: motivations and management. [PDF](https://pdfs.semanticscholar.org/f2a2/c5129cf5656af7acc7ffaf84c9c9bafe72c5.pdf)

* Jiménez et al. (2017).Four simple recommendations to encourage best practices in research software. [doi.org/10.12688/f1000research.11407.1](https://doi.org/10.12688/f1000research.11407.1) 

* Martinez-Torres and Diaz-Fernandez (2013).Current issues and research trends on open-source software communities [PDF](https://idus.us.es/xmlui/bitstream/handle/11441/32245/Current%20issues%20and%20research%20trends.pdf?sequence=1) 

* Morin et al. (2012). Shining Light into Black Boxes. [PDF](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4203337/pdf/nihms588981.pdf)

* Oishi et al. (2018). Perspectives on Reproducibility and Sustainability of Open-Source Scientific Software from Seven Years of the Dedalus Project. [arXiv:1801.08200v1 [astro-ph.IM]](https://arxiv.org/abs/1801.08200)

* Scacchi (2010). The Future of Research in Free/Open Source Software Development. [PDF](http://www.ics.uci.edu/~wscacchi/Papers/New/FoSER-Scacchi-2010.pdf)

* Sandve et al. (2013). Ten simple rules for reproducible computational research [doi.org/10.1371/journal.pcbi.1003285](https://doi.org/10.1371/journal.pcbi.1003285) 

* Shamir et al. (2013).Practices in source code sharing in astrophysics. [arXiv:1304.6780v1 [astro-ph.IM]](https://arxiv.org/abs/1304.6780) 

* Steinmacher et al. (2014). A systematic literature review on the barriers faced by newcomers to open source software projects. [PDF](http://igor.pro.br/publica/papers/IST_SysReview_PrePrint.pdf) 

* Stodden (2010). The Scientific Method in Practice: Reproducibility in the Computational Sciences.[PDF](http://datascienceassn.org/sites/default/files/The%20Scientific%20Method%20in%20Practice%20-%20Reproducibility%20in%20the%20Computational%20Sciences.pdf)

* Vandewalle (2012). Code Sharing Is Associated with Research Impact in Image Processing. [PDF](https://infoscience.epfl.ch/record/206184/files/Vandewalle12.pdf) 
