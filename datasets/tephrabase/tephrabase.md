# Tephrabase
**Creator:** Anthony Newton

**Description:** Tephrabase contains details of tephra layers at over 1000 sites in Europe and over 400 of these are in Iceland. The Icelandic tephra layers range from the early Holocene period to the most recent eruptions. Many of the tephra layers erupted since the settlement of Iceland in the 9th century have been precisely dated from ice core dating and using historical sources. This has produced an unparalleled chronology which can be used date archaeological sites and palaeoenvironmental records, enabling correlations between the two and rates of environmental change to be studied.

**Publisher:** University of Edinburgh

**Contributor(s):** 

**Created:** 1995

**DCMI Type:** dataset

**Format** JSON

**Language(s):** English

**Relation:** 

**Subject(s):** ([FISH Vocabularies](http://www.heritage-standards.org.uk/fish-vocabularies/)) - 
[Archaeological Objects](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/ObjType_class.pdf): Tephra
[Archaeological Sciences](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/ArchSci_class.pdf): Tephrochronology, Palaeoenvironmental Analysis, Stratigraphic Description;
[Events](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/Event_class.pdf):  Test Pit, Environmental Sampling, Geomorphological Survey;
[Historic Characterization](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/HistoricCharacter_class.pdf): Palaeolandscape Component, Peat Deposit

**Extent, spatial:** Iceland

**Extent, temporal:** 750-2011 CE

**License:** CC-BY

**Field List:**
| Field Name	| Field Type	| Field Title	| Field Description	|
|:----|:--------------------|:--------------------:|:--------------------|
|teph_sitenumber | number | Teph Sitenumber | Unique Tephrabase number given to each site |
|teph_sitename| string | Teph Sitename | Name of site |
|teph_profilenumber | number | Teph Profilenumber| Unique Tephrabase number given to each profile at each site (usually just one per site) |
|teph_profilename | string | Teph Profilename | Name given to the profile (core, soil section, pit etc) at each site. |
|teph_earliestyear | string | Teph Earliestyear | The youngest date from the profile, which is usually the date the profile was dug. This date can be used in sediment accumulation rate calculations.|
| teph_latestyear | string | Teph Latestyear | The year the oldest tephra layer found in that profile was deposited |
| teph_tephra_tephraname | string| Teph Tephra Tephraname | The name of the tephra (volcanic ash) layer. Tephra is composed of any particulate material transported through the air during an eruption and can be composed of volcanic glass, minerals, rock fragments.|
| teph_tephra_tephranumber | number| Teph Tephra Tephranumber | Unique Tephrabase number given to each tephra layer|
| teph_tephra_tephrayear | number| Teph Tephra Tephrayear | The year that the tephra layer was deposited (if available)|
| teph_tephra_tephraldepth | number| Teph Tephra Tephraldepth |The depth from the surface to the lower boundary of the tephra layer in meters|
| teph_tephra_tephraudepth | number| Teph Tephra Tephraudepth | The depth from the surface to the upper boundary of the tephra layer in meters|
| teph_tephra_tephrareference | number| Teph Tephra Tephrareference | Unique Tephrabase reference number, which links to publication or source details in Tephrabase |
| teph_tephra_tephraorder | number| Teph Tephra Tephraorder | The order of the tephra layer in the profile (starting with 1 at the top of the profile)a |
| teph_tephra | array| Teph Tephra | All of the details for each tephra layer in a profile [an array] |



