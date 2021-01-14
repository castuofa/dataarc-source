# DATASET TITLE
**Creator:** University of Arkansas, Center for Advanced Spatial Technologies; Christopher Angel
 
**Description:**  Four datasets were generated from the NABO Publication PDFs. Using a PDF tool developed at the Center for Advanced Spatial Technologies each PDF found on this page were analyzed. Text and text location were extracted and stored for each file. Results are organized to align with the four publications sections found on the NABO Publications page; these sections include the following: 1) Fornleifastofnun Íslands (FSÍ) Archaeological Reports (naboreports_fsi.geojson); 2) Field Reports (naboreports_field.geojson); 3) NABO Laboratory Reports (naboreports_lab.geojson); 4) International Polar Year (IPY) Reports (naboreports_ipy.geojson).

**Abstract:**  

**Publisher:** University of Arkansas, Center for Advanced Spatial Technologies

**Contributor(s):** North Atlantic Biocultural Organisation

**Created:** 11/07/2020

**DCMI Type:** Dataset

**Format:** JSON

**Language(s):** English, Icelandic

**Relation:**  [NABO Publications](https://www.nabohome.org/publications/publications.html)

**Subject(s):** ([FISH Vocabularies](http://www.heritage-standards.org.uk/fish-vocabularies/)) - 
[Archaeological Objects](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/ObjType_class.pdf): Not applicable
[Archaeological Sciences](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/ArchSci_class.pdf): Not applicable
[Events](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/Event_class.pdf):  Not applicable
[Historic Characterization](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/HistoricCharacter_class.pdf): Not applicable

**Extent, spatial:** Varies

**Extent, temporal:** Varies

**License:** CC BY-NC

**Field List:**
| Field Name | Field Type | Field Title | Field Description |
|:----|:--------------------|:--------------------:|:--------------------|
|type | string | Type | The type of geometry being stored. |
|coordinates | number | Coordinates | The coordinates for the geometry. Note that this field will alwasy be NULL in this dataset. |
|title | string | Title | This title reflects the document title as listed on the NABO Publications website for the report and/or publication being referenced in the record. |
|content | string | Content | Content includes the literal text that was pulled from one quarter of the PDF page. |
|content_count | number | Content count | Count of text objects in within the content analyzed. |
|words | number| Words | Count of unique words within the content analyzed. Words listed multiple times are only counted once. |
|page | number | Page | The PDF page number on which the content resides that has been analyzed. |
|filename | string | Filename | The name of the pdf file that has been analyzed in creating this content. |
|url | string | URL | The url location, at the time of processing, of the file that has been analyzed in the creating this content. |
|page_count | number | Page count | The total number of pages in the PDF that has been analyzed to create the content. |
|section | number | Section | The section of the page from which the content was generated. |
|section_count | number | Section count | The total number of sections on the page for which content was analyzed.|