---
description: Create an entry based on an ID such as DOI or ISBN.
---

# Add entry using an ID

## From an ID to an entry

Simply paste the DOI into the table of entry, and JabRef will create the new corresponding entry.

For other identifiers, choose **Library → New entry**, or click on the `New entry` button, or use the keyboard shortcut `CTRL + N`. In the lower part of the window, there are two boxes : "ID type" and "ID". In the field "ID type", you can select the desired identifier, e.g. "ISBN" \(it works also for DOI\). Then enter the identifier in the textbox below and press Enter. That will generate an entry based on the given ID \(you can also click on "Generate"\). The entry is added to your library and opened in the entry editor. In case an error occurs, a popup is shown.

![](../.gitbook/assets/entrytype-dialog.png)

> _NOTE:_ The content in the dialog depends on the database mode

{% hint style="info" %}
Sometimes the new entry contains a`url`field. This field usually points to the URL of the book at the respective online book store. In case you buy the book using this link, the service provider \(e.g. ebook.de\) receive a commission to fund the service.
{% endhint %}

## Supported databases

### Arxiv

### Crossref

### ISBN

First, [eBook.de's](https://www.ebook.de/de/) API is used to fetch bibliographic information based on the ISBN. If no entry is found, the JabRef tries [OttoBib](https://www.ottobib.com/) to get data.

### DiVA

[DiVA \(Digitala Vetenskapliga Arkivet\)](https://info.diva-portal.org/about-diva/) is a database with publications from about [40](https://www.diva-portal.org/smash/aboutdiva.jsf) Swedish universities and research institutions.

### DOI

JabRef uses [http://dx.doi.org/](http://dx.doi.org/) \(provided by [http://crossref.org/](http://crossref.org/)\) to convert the given DOI to a new entry.

### IACR eprints

The [International Association for Cryptologic Research](https://www.iacr.org/) maintains an eprint archive to which anyone can submit papers and technical reports. These eprints are given IDs based on the year of submission, e.g. the 10th submission in 2018 gets the ID "2018/10". To get the ID, you may want to use their web search form at [https://eprint.iacr.org/search.html](https://eprint.iacr.org/search.html).

### Library of congress

### MathSciNet

### Medline/Pubmed

[Medline/Pubmed](https://www.nlm.nih.gov/bsd/medline.html) is a bibliographic database of life sciences and biomedical information. It includes bibliographic information for articles from academic journals covering medicine, nursing, pharmacy, dentistry, veterinary medicine, and health care. Medline also covers much of the literature in biology and biochemistry, as well as fields such as molecular evolution \([Wikipedia](https://en.wikipedia.org/wiki/MEDLINE)\).

### mEDRA

### SAO/NASA ADS

[SAO/NASA Astrophysics Data System](http://www.adsabs.harvard.edu/) is an online database of over eight million astronomy and physics papers from both peer reviewed and non-peer reviewed sources. Abstracts are available free online for almost all articles, and full scanned articles are available in Graphics Interchange Format \(GIF\) and Portable Document Format \(PDF\) for older articles \([Wikipedia](https://en.wikipedia.org/wiki/Astrophysics_Data_System)\).

### Title

### **RFC**

[IETF \(Internet Engineering Task Force\)](https://datatracker.ietf.org/) Datatracker is a database that "contains data about the documents, working groups, meetings, agendas, minutes, presentations, and more, of the IETF." The RFC number \(Request for Comments number\) is an ID type specific to the IETF database.

