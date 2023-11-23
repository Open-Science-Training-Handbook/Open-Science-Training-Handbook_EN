## <img src="/Images/Icons/open_licenses.png" width="200" height="200" />
## 6. Open Licensing and File Formats

### What is it?

A license is a legal document that grants specific rights to user to reuse and redistribute a material under some conditions. Any right that is not granted by default by the licensor through the license can be asked. Licenses can be applied to any material \(e.g., sound, text, image, multimedia, software\) where some exploitation or usage rights exist.

[Free con](https://en.wikipedia.org/wiki/List_of_free_content_licenses)[tent license](https://en.wikipedia.org/wiki/List_of_free_content_licenses)[s](https://en.wikipedia.org/wiki/List_of_free_content_licenses) are licenses that grant permission to access, re-use, and redistribute material with few or no restrictions. Those licenses range from very open to very restrictive. The more restrictions, the more difficult it becomes to combine differently licenses content—thus potentially preventing interoperability.

A file format is a standard way that information is encoded for storage in a computer file; however, not all formats have freely available specification documents, partly because some developers view their specification documents as trade secrets.

![](/Images/02%20Open%20Science%20Basics/02_open_licensing.png)

### Rationale

Applying an open license to a scientific work \(whether it is an article, dataset or other type of research output\) is a way for the copyright holder to express the conditions under which the work can be accessed, re-used and modified.

It is important to know that a license builds on existing copyright regulations. In other words: you can only license content if you are the rights owner, and you cannot license any forms of reuse if they do not fall under existing copyright regulations.

When sharing any open content it is not enough to attach a license you must take into account the format. A choice of a non-open file format may make impossible to reuse the content. For that reason is important to know the options available when deciding in which format you want to share your content.

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Learning objectives

1. Participants should learn about differences among licenses and how they can suit some open-science definitions, open-science requirements, or how they fit into different research outcomes.

2. Learn about the different building blocks of licenses, such as attribution, \(non-\)commercial, derivatives, etc.

3. Learn the importance of defining who holds the copyright or related rights of research output.

4. Learn about the differences between proprietary and open file formats, and how these can prevent or facilitate reusability and interoperability.

### Key components

## <img src="/Images/Icons/brain.png" width="150" height="150" /> <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Knowledge & Skills

Basic concepts of copyright are needed in order to understand how the licenses work. Since copyright laws are not internationally harmonized you must refer to the applicable laws in your context.

Among the range of free content licenses there are the copyleft licenses, originated in the free software community, that allow a broad reuse of materials under the condition that any new material build upon the existing one must be licensed under the same license. This fact has brought some interoperable problems that newer versions overcomed by stating that the derived materials should be licensed under the same terms of the original license.

The most used licenses for scientific content are [Creative Commons licenses](https://creativecommons.org/licenses/). In general, a CC BY license \(requiring only attribution\) is a good option for works such articles, books, working papers, and reports while a dedication to the public domain using CC Zero (CC0) is recommended for datasets and databases \(NOTE:  In the US and EU, individual facts cannot be copyrighted, although collections of facts that underwent some creative selection or organization may be copyrighted. Additionally, in the EU there is a sui generis right granted to the maker of a database for the investment made in its compilation, even when this does not involve any creativity.\). Creative Commons licenses should not be used for licensing software because they were not designed for that purpose, as the organisation states. Instead, software developers should use appropriate licenses like those collected by the [Open Source Initiative](https://opensource.org/licenses) or [Free Software Foundation](https://www.fsf.org/licensing/). You can check your options at [choosealicense](https://choosealicense.com).

CC0 was originally created as a legal tool to release scientific databases without any restriction, and especially to overcome the different treatments of legal protection when publishing a database. CC0 has been seen as a tool for dedicating works to the public domain but it is more than a simple waiver. CC0 is a three-step instrument built to allow its use in jurisdictions where a full public domain dedication is not possible \(for instance in many continental Europe countries\). First, by using CC0, the copyright holder waives any right to the maximum extent allowed by applicable law. Second, if there is any remaining unwaivable right, CC0 acts as a license to grant any of those remaining rights without any restriction or obligation. And finally, the copyright holder asserts not to enforce any right that could not been possible to waive or grant by the applicable law. The idea behind CC0 is to convince researchers to follow community norms instead of using licenses in materials as a database where, in many cases, its contents are uncopyrightable.

As a trainer, you may show the differences among licenses and how they can suit some of the Open Science definitions, the Open Science requirements or how they fit into different research outcomes. Depending on the prior knowledge of your audience, you can give an overview of the different building blocks \(attribution, \(non-\)commercial, derivatives, etc.\) of the licenses in general or provide a detailed analysis of each building block and its effects on re-use and interoperability. As copyright rules vary greatly per jurisdiction \(common law vs. civil law countries, but also within the European Union\), usability of licenses can vary greatly. This can be discussed in detail if the audience has previous knowledge about licensing, but if they are relatively new to the subject this should not be discussed in detail.

Core licensing items to consider \(from the [Data Packaging Guide](https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md)\):

* Choosing an open license.

* Stating the chosen license clearly and prominently, preferably in a machine readable format.

* Explain the liberations/limitations of the chosen license, and what barriers or restrictions may apply.

* Let users know where they can find more information about this license.

* Explain that the license applies to the data, and not the content that the data represents \(an open license on the metadata is not the same as the content itself being open, out of copyright, or able to be used freely\).

* Explain why this license was chosen.

Training should provide an overview of intellectual property policies in universities and public research institutions. It is important to stress the need to define who holds copyright or any other related rights of the research output. The copyright holder is the one who can decide to lift restrictions if they are not lifted by default through the licenses. Regarding research outputs, the copyright holder can be a researcher, a publisher, a scientific society, a research institution, a funder, etc.

Within the context of Open Science, and for optimal long-term archiving, files should not be compressed and should avoid proprietary or patent-encumbered formats and in favor of open formats based on documented standards. This ensures the access and re-usability of the content. Only unencrypted files should be published and archived. Examples for open file formats are:

* Text: TXT, ODT, PDF/A, XML

* Tabular data: CSV, TSV

* Image: TIFF, PNG, JPG 2000, SVG, WebP

* Audio: WAV, FLAC, OPUS

* Video: MPEG2, Theora, VP8, VP9, AV1, Motion JPG 2000 \(MJ2\),

* Binary hierarchical data: HDF5

Some file formats cannot be converted to open formats, but are nonetheless archived. They are often device-specific, but have a broad user community. Check if the repository where you want to deposit a publication has a list of preferred formats.

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Questions, obstacles, and common misconceptions

Q: "Why should I use the CC-BY license for my written/creative content?"

A: The CC-BY license is the most permissive license that also retains some rights for the creators—the only requirement is that someone who uses, modifies, or distributes the content attributes the original creator. Other attributes of Creative Commons licenses include No Derivatives \(ND\), Non-Commercial \(NC\), and Share Alike \(SA\), which add additional restrictions that may limit the potential use and impact of your work. Preventing derivatives with ND strongly limits the impact and use of your work, since no one else will be able to build on what you have done. Similarly, while many researchers may prefer the NC limitation to prevent companies from commercializing or making money on their work, strictly defining commercial use is challenging. Furthermore, the intent of much publicly funded research is to lead to economic development through \(ventual\) commercial use, which would be prevented by this license. Using an SA license allows reuse and distribution, but requires downstream works to apply the same license, limiting use and combination with other works.

A common fear when using CC0 is that the attribution requirement is dropped—however, proponents state that attribution is a key element in good scientific practice, regardless of copyright status of license conditions of the quoted work. Some repositories applying CC0 explicitly mention attribution, cf., e.g., this example from Dataverse: "Our Community Norms as well as good scientific practices expect that proper credit is given via citation. Please use the data citation above, generated by the Dataverse."

Obstacle: different countries have different copyright laws, which may limit the ability to choose any license or dedicate work to the public domain. For example, in Germany and other European countries it is not possible to fully waive copyright, and thus fully dedicating work to the public domain is not legally possible. Instead, the CC0 license can be used as an "effective" public domain license that allows unrestricted use.

Interoperability of licenses: be aware that sometimes when you mix content licensed differently it may be impossible to release the derivative work. For example, material distributed with an SA license can only be combined with other SA-licensed content.

Suitability of licenses: for instance, CC licenses should not be used for software, there are specific licenses for databases \(Open Data Commons\), and CC licenses were not suitable for databases before version 4.0.

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Learning outcomes

1. Will be able to use existing resources to choose an appropriate license for written research work, based on the desired freedom/limitation for others to use/reuse.

2. Will be able to use existing resources to choose an appropriate license for data, based on the desired freedom/limitation for others to use/reuse.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Further reading

* Creative Commons License Picker. [creativecommons.org](https://creativecommons.org/choose/)

* How to License Research Data. [dcc.ac.uk](http://www.dcc.ac.uk/resources/how-guides/license-research-data)

* Klimpe (2012). Free knowledge thanks to Creative Commons Licenses - Why a non-commercial clause often won‘t serve your needs. [Original PDF in German](https://irights.info/wp-content/uploads/userfiles/CC-NC_Leitfaden_web.pdf), [English translation PDF](openglam.org/files/2013/01/iRights_CC-NC_Guide_English.pdf)

* Kreutzer (n.y.). Validity of the Creative Commons Zero 1.0 Universal Public Domain Dedication and its usability for bibliographic metadata from the perspective of German Copyright Law. [PDF](https://www.rd-alliance.org/sites/default/files/cc0-analysis-kreuzer.pdf)

* List of open formats. [Wikipedia](https://en.wikipedia.org/wiki/List_of_open_formats)

* Open Content - A Practical Guide to Using Creative Commons Licences/The Creative Commons licencing scheme. [meta.wikimedia.org](https://meta.wikimedia.org/wiki/Open_Content_-_A_Practical_Guide_to_Using_Creative_Commons_Licences/The_Creative_Commons_licencing_scheme)

* Open Definition. Licenses. [opendefinition.org](http://opendefinition.org/licenses/)

* Open Source Licensing. [opensource.org/licenses](https://opensource.org/licenses)

* Redhead (2012). Why CC-BY?. Open Access Scholarly Publishers Association. [oaspa.org/why-cc-by](https://oaspa.org/why-cc-by/)

* World Intellectual Property Organization. Universitites and Intellectual Property. [wipo.int](http://www.wipo.int/about-ip/en/universities_research/)



