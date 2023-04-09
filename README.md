# Awesome PDF  [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
A curated list of resources around PDF files

## The File Format

* PDF Association: [PDF Specification Index](https://www.pdfa.org/resource/pdf-specification-index/), 2021.
* Jindrich Kubec, Jiri Sejtko: [X is not enough! Grab the PDF by the tail!](https://www.virusbulletin.com/uploads/pdf/conference_slides/2011/Kubec-Sejtko-VB2011.pdf) at [Virus Bulletin](https://www.virusbulletin.com/), 2011.
* Selected compilation of PDF Standards from the [Adobe Open Source Reference](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/acrobatsdk/#pdf-reference), 2022.
  1. [PDF Reference 1.0](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/pdfreference1.0.pdf)
  2. [PDF Reference 1.2](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/pdfreference1.2.pdf)
  3. [PDF Reference 1.3](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/pdfreference1.3.pdf)
  4. [PDF Reference 1.4](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/pdfreference1.4.pdf)
  5. [PDF Reference 1.5 (v6)](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/pdfreference1.5_v6.pdf)
  6. [PDF Reference 1.6](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/pdfreference1.6.pdf)
  7. [PDF Reference 1.7 (ISO 32000, 2008)](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/PDF32000_2008.pdf)
  8. [PDF Reference 2.0 (ISO 32000-2:2020)](https://www.pdfa-inc.org/product/iso-32000-2-pdf-2-0-bundle-sponsored-access/) (freely available ISO standard due to corporate sponsorship)
* Adobe: [XMP Specification Part 3](https://github.com/adobe/xmp-docs/blob/master/XMPSpecifications/XMPSpecificationPart3.pdf), January 2020.


## Viewers

* [KOReader](https://github.com/koreader/koreader): a document viewer primarily aimed at e-ink readers
* [react-native-pdf](https://github.com/wonday/react-native-pdf): a react native PDF view component
* [PdfViewPager](https://github.com/voghDev/PdfViewPager): Android widget to display PDF documents in your Activities or Fragments
* [vue-pdf](https://github.com/FranckFreiburger/vue-pdf): vue.js pdf viewer

## Data Extraction

* [pdftotext](https://manpages.debian.org/stretch/poppler-utils/pdftotext.1.en.html): an application that converts Portable Document Format (PDF) files to plain text. Part of poppler-utils.
* [pdfminer.six](https://pypi.org/project/pdfminer.six/): a Python library for extracting information from PDF documents
    * [pdfplumber](https://github.com/jsvine/pdfplumber): Plumb a PDF for detailed information about each text character, rectangle, and line. Plus: Table extraction and visual debugging.
* [Tabula](https://github.com/tabulapdf/tabula): an application for extracting tables
* [camelot](https://github.com/atlanhq/camelot): PDF Table Extraction
* [awesome-document-understanding](https://github.com/tstanislawek/awesome-document-understanding): A curated list of resources for Document Understanding (DU) topic

## Generators

Anything that can produce PDF files from scratch:

* pdflatex (e.g. in [TexLive](https://www.tug.org/texlive/)): A LaTeX-to-PDF converter
* [reportlab](https://pypi.org/project/reportlab/): The ReportLab Toolkit. An Open Source Python library for generating PDFs and graphics.
* [prawn](https://github.com/prawnpdf/prawn): a pure Ruby PDF generation library
* [react-pdf](https://github.com/diegomura/react-pdf): Create PDF files using React
* [markdown-pdf](https://github.com/alanshaw/markdown-pdf): Markdown to PDF converter
* [mpdf](https://github.com/mpdf/mpdf): PHP library generating PDF files from UTF-8 encoded HTML

## Manipulators

Anything that's used to edit an existing PDF file:

* [pdfarranger](https://github.com/pdfarranger/pdfarranger): a small python-gtk application, which helps the user to merge or split pdf documents and rotate, crop and rearrange their pages using a graphical interface
* [OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF): adds an OCR text layer to scanned PDF files, allowing them to be searched

## File Analysis / Security

* [Pdfalyzer](https://github.com/michelcrypt4d4mus/pdfalyzer): PDF analysis tool to visualize the internal data structure of a PDF in large and colorful diagrams as well as scanning the binary streams embedded in the PDF against a collection of malicious PDF specific YARA rules.
* [Malicious PDF Generator](https://github.com/jonaslejon/malicious-pdf): generate a bunch of malicious pdf files with phone-home functionality
* [pdfbox](https://pdfbox.apache.org/1.8/commandline.html): tool in java to browse internally a pdf. [Download](https://pdfbox.apache.org/download.cgi) and use as `pdfbox-app-x.y.z.jar debug pdf_file`

## Multi-Purpose Libraries

* [pdftk](https://www.pdflabs.com/tools/pdftk-server/): command-line tool for working with PDFs. It is commonly used for client-side scripting or server-side processing of PDFs.
* [PyPDF2](https://pypi.org/project/PyPDF2/) ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive): a free and open-source pure-python PDF library capable of splitting, merging, cropping, and transforming the pages of PDF files
* [pikepdf](https://github.com/pikepdf/pikepdf) ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive): a Python library for reading and writing PDF, powered by qpdf
* [PyMuPDF](https://github.com/pymupdf/PyMuPDF) ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-render-inactive): Python bindings to MuPDF.
* [pypdfium2](https://github.com/pypdfium2-team/pypdfium2) ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive) ![](https://shields.io/badge/-render-inactive): Python bindings to PDFium.
* [borb](https://github.com/jorisschellekens/borb) ![](https://shields.io/badge/-extract-inactive)  ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive): reading, creating and manipulating PDF files in python
* [pdfcpu](https://github.com/pdfcpu/pdfcpu) ![](https://shields.io/badge/-extract-inactive)  ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive): batch processing and scripting via a rich command line
* [pdf-lib](https://github.com/Hopding/pdf-lib)  ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive): Create and modify PDF documents in any JavaScript environment
