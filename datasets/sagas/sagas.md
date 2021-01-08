# Icelandic Saga Map
**Creator:** Emily Lethbridge

**Description:** The Icelandic Saga Map database contains geo-referenced texts in Icelandic and English, with specific emphasis on medieval Icelandic sagas. All geographical places mentioned in the texts are displayed on a map interface with the text alongside. Other data pertains to medieval and post-medieval parchment and paper manuscripts of the geo-referenced saga texts, and to Icelandic travel books.

**Abstract:** The Icelandic Saga Map database contains geo-referenced texts in Icelandic and English, with specific emphasis on medieval Icelandic sagas. All geographical places mentioned in the texts are displayed on a map interface with the text alongside.

**Publisher:** University of Iceland

**Contributor(s):** Trausti Dagsson, Pétur Húni Björnsson, Logi Ragnarsson, Zachary Melton, Gísli Pálsson, Hjördís Erna Sigurðardóttir, Nikola Machackova

**Created:** 2015

**DCMI Type:** dataset

**Format** JSON

**Language(s):** English, Icelandic

**Relation:** Documentary research: http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/Event_class.pdf

**Extent, spatial:** Iceland, Norway, Denmark, Sweden, Greenland, Faroe Islands, United Kingdom, North America

**Extent, temporal:** 750 CE - 2,017 CE (with focus on 750 CE - 1,250 CE)

**License:** CC BY-NC

**Field List:**
|Remove | Field Name	| Field Type	| Field Title	| Field Description	|
|:----|:--------------------|:--------------------:|:--------------------:|:--------------------|
||sagas_id | number | Sagas ID | The unique saga identification number assigned in the Icelandic Saga Map (ISM) |
||sagas_name | string | Sagas Name | Title of the written work (e.g. Laxdæla saga) |
|x|sagas_sagaid | number | Sagas Sagaid | The unique saga identification number assigned in the Icelandic Saga Map (ISM) |
|x|sagas_saganmae | string | Sagas Saganame | Title of the written work (e.g. Laxdæla saga) |
| |sagas_type | string | Sagas Type (Place Type) | This is Place Type and the field should be renamed as such. Type of physical place, whether natural or manmade (e.g. farm, valley, harbor, etc.)|
| | sagas_chapter | string | Sagas Chapter | Number of chapter within saga. (e.g. 1 kafli (Chapter 1)) |
| | sagas_chapternr | number | Sagas Chapter Number | Chapter number (number only) |
| | sagas_action_start | string | Sagas Action Start | Year in Common Era (CE) noting the beginning of action in the saga|
| | sagas_action_end | string | Sagas Action End | Year in Common Era (CE) noting the beginning of action in the saga|
| | sagas_composition_start | string | Sagas Composition Start |Year in Common Era (CE) marking earliest time of written composition for a text |
| | sagas_composition_end | string | Sagas Composition End | Year in Common Era (CE) marking earliest time of written composition for a text |
| | sagas_oldest_manuscript | string | Sagas Oldest Manuscript | Accession number for the oldest manuscript for this saga |
| | sagas_oldest_manuscript_start | string | Sagas Oldest Manuscript Start | Year in Common Era (CE) marking the earliest date of production of the oldest manuscript of given saga |
| | sagas_oldest_manuscript_end | string | Sagas Oldest Manuscript End | Year in Common Era (CE) marking the earliest date of production of the oldest manuscript of given saga |
| | sagas_manuscript_link | string | Sagas Manuscript Link | URL to the online manuscript catalog with digital images and additional information|


<!-- Field Name: sagas_id
Field Type: number
Field Title: Sagas Id
Field Description: The unique saga identification number assigned in the Icelandic Saga Map (ISM)

Field Name: sagas_name
Field Type: string
Field Title: Sagas Name
Field Description: Title of the written work (e.g. Laxdæla saga)

Field Name: sagas_sagaid
Field Type: number
Field Title: Sagas Sagaid Emily needs to remove from dataset when uploaded
Field Description: The unique saga identification number assigned in the Icelandic Saga Map (ISM)

Field Name: sagas_saganame
Field Type: string
Field Title: Sagas Saganame Emily needs to remove from dataset when uploaded
Field Description: Title of the written work (e.g. Laxdæla saga)

Field Name: sagas_type
Field Type: string
Field Title: Sagas Type (Place Type)
Field Description: This is Place Type and the field should be renamed as such. Type of physical place, whether natural or manmade (e.g. farm, valley, harbor, etc.)

Field Name:  sagas_chapter
Field Type:  string
Field Title:  Sagas Chapter
Field Description:  Number of chapter within saga. (e.g. 1 kafli (Chapter 1))

"Field Name: sagas_chapternr
Field Type: number
Field Title: Sagas Chapter Number
Field Description: Chapter number (number only)

Field Name: sagas_action_start
Field Type: string
Field Title: Sagas Action Start
Field Description: Year in Common Era (CE) noting the beginning of action in the saga

Field Name: sagas_action_end
Field Type: string
Field Title: Sagas Action End
Field Description: Year in Common Era (CE) noting the end of action in the saga

Field Name: sagas_composition_start
Field Type: string
Field Title: Sagas Composition Start
Field Description: Year in Common Era (CE) marking earliest time of written composition for a text

Field Name: sagas_composition_end
Field Type: string
Field Title: Sagas Composition End
Field Description: Year in Common Era (CE) marking latest time of written composition for a text

Field Name: sagas_oldest_manuscript
Field Type: string
Field Title: Sagas Oldest Manuscript
Field Description: Accession number for the oldest manuscript for this saga

Field Name: sagas_oldest_manuscript_start
Field Type: string
Field Title: Sagas Oldest Manuscript Start
Field Description: Year in Common Era (CE) marking the earliest date of production of the oldest manuscript of given saga

Field Name: sagas_oldest_manuscript_end
Field Type: string
Field Title: Sagas Oldest Manuscript End
Field Description: Year in Common Era (CE) marking the latest date of production of the oldest manuscript of given saga

Field Name: sagas_manuscript_link
Field Type: string
Field Title: Sagas Manuscript Link
Field Description: URL to the online manuscript catalog with digital images and additional information
!-->



