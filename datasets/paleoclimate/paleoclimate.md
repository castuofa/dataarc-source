# Climate Iceland
**Creator:** Willem Koster

**Description:** The Climate Iceland is dataset is a collection of data from climate studies in the North Atlantic. Temperature reconstructions or ice sheet reconstructions are present. This database does not hold any data, rather, it contains important information about the studies and links to the actual data.

**Publisher:** Willem Koster

**Contributor(s):** NOAA (National Oceanic and Atmospheric Administration), Richard Streeter

**Created:** 9/1/2020

**DCMI Type:** dataset

**Format:** CSV, TXT, JSON

**Language(s):** English

**Relation:** Refer to Database_link1 field

**Subject(s):** ([FISH Vocabularies](http://www.heritage-standards.org.uk/fish-vocabularies/)) - 
[Archaeological Objects](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/ObjType_class.pdf): Tephra;
[Archaeological Sciences](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/ArchSci_class.pdf): Radiocarbon Dating, Tephrochronology, Specialist Sampling, Foraminifera Analysis, Diatom Analysis;
[Events](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/Event_class.pdf):  Tephra, Core sampling;
[Historic Characterization](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/HistoricCharacter_class.pdf): N/A

**Extent, spatial:** Iceland, Greenland, Faroe Islands

**Extent, temporal:** 13,500 BCE - Present

**License:** CC BY-NC-ND

**Field List:**
| Field Name	| Field Type	| Field Title	| Field Description	|
|:----|:--------------------|:--------------------:|:--------------------|
|objectid| number| Objectid| Unique identifier|
|elev| elev| Elev| Elevation (in case of terrestrial cores), or ocean water depth (in case of marine cores)|
|site_name| string| Site Name| Name of the site the core was taken as registered in the metadata associated with the study|
|id| number| Id| Sequential number based on time of entry|
|date_core_taken| string| Date Core Taken| Date that the core was taken, recorded as year-month-day|
|data_available| string| Data Available| Is the data available online or not (y/n)|
|source| string| Source| Type of sediment that was cored|
|reconstruction| string| Reconstruction| The reconstruction that was made from (some of) the proxies|
|proxy| string| Proxy| The proxies that were recorded in the studies. Values used in this dataset include Q/K_feldspar ( ), magn_data (), chironomids (), quartz(), calcite (), shell_growth_increments (), Mg/Ca (), d18O (), forams (), carbonates (), diatoms (), alkenones (), ACL25-35 (), UK’37 (), CBT (), dD (), d13C ().|
|oldest_date_bp| number| Oldest Date Bp| The oldest dated layer recorded in the core (does not mean the bottom of the core) recorded in calendar years BP (Before Present)|
|youngest_date_bp| number| Youngest Date Bp| The youngest dated layer recorded in the core (does not mean the top of the core) recorded in calendar years BP (Before Present)|
|dating_method| string| Dating Method| Type of dating used (radiometric, tephrochronology)|
|youngest_date_ce| number| Youngest Date Ce| The youngest dated layer recorded in the core (does not mean the top of the core) recorded in calendar years CE (Common Era)|
|number_of_samples| number| Number Of Samples| Type of dating used (radiometric, tephrochronology)|
|oldest_date_ce| number| Oldest Date Ce| The oldest dated layer recorded in the core (does not mean the bottom of the core) recorded in calendar years CE (Common Era)|
|num_dates| number| Num Dates| The number of dated layers in the core|
|sampling_resolution| number| Sampling Resolution| The average number of time passed between two proxy samples (in years). Calculated as|
|database_link| string| Database Link| If applicable, a link to an online database where the data and/or the metadata is available|
|reference| string| Reference| Reference to the paper in which the core/study was published|
|latitude| number| Latitude| Latitude in decimal degrees as registered in metadata|
|longitude| number| Longitude| Longitude in decimal degrees as registered in metadata|
|database_link2| string| Database Link2| If applicable, a second link to an online database where the data and/or the metadata is available|




