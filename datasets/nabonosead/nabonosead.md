# NABONOSEAD
**Creator:** Thomas H. McGovern, Thomas J. Ryan Jr., Philip Buckland

**Description:**  NABONE was designed as a package to allow for consistent recording and reporting of zooarchaeological (animal bone) data from archaeological sites. The package was developed in 1995-97 following an NSF funded workshop at Hunter College CUNY that brought together 27 active zooarchaeologists working in the N Atlantic/ Arctic areas and was an attempt to synthesize then current best practice approaches while allowing considerable flexibility for the user. The package consists of an MS Access database, specialized MS Excel files for calculation and graphics, and MS Word files for the coding and recording manual (now version 9) and any analysis notes. Multiple projects have used this system, especially those working with CUNY trained zooarchaeologists and most of the zooarchaeological record for Iceland and Greenland since 1997 is recorded on this system. The records are by taxon (to species level where possible but including more general levels such as "fish sp. unidentified") and record the variables "END ", "SIZE", "FUSION STATE", "BUTCHERY", "BURNING","GNAWING","AGE","SEX", plus tooth eruption and wear (following Grant 1982), and metrics (following Von Den Dreisch 1976). The package is being upgraded and modernized 2020-22.

**Abstract:**  NABONE was designed as a package to allow for consistent recording and reporting of zooarchaeological (animal bone) data from archaeological sites. The package was developed in 1995-97 following an NSF funded workshop at Hunter College CUNY that brought together 27 active zooarchaeologists working in the N Atlantic/ Arctic areas and was an attempt to synthesize then current best practice approaches while allowing considerable flexibility for the user.

**Publisher:** Bioarchaeological Labratory, Department of Anthropology, Hunter College, City University of New York

**Contributor(s):**   Sophia Perdikaris, James Woollett, Gavin Lucas, Adolf Friðriksson, Orri Vésteinsson, Howell Roberts, Hildur Gestsdóttir, George Hambrecht, Ragnar Edvardsson, Colin Amundsen, Arnar Már Vilhjálmsson, Sigríður Þorgeirsdóttir, Magnús Á. Sigurgeirsson, Seth Brewington, Ramona Harrison, Konrad Smiarowski, Megan Hicks, Peter Kuchar, Albina Palsdóttir, Caroline Paulsen, Andrea Harðardóttir, James Taylor, Torfi H. Tulinius

**Created:** 1990

**DCMI Type:** dataset

**Format:** Access, PostgreSQL, JSON

**Language(s):** English

**Relation:**  NABONE, NABO [https://www.nabohome.org/](https://www.nabohome.org/)

**Extent, spatial:** Greenland, Iceland, Faroe Islands

**Extent, temporal:** 750 CE - 2,017 CE

**License:** CC BY-NC-SA

**Field List:**
| Field Name	| Field Type	| Field Title	| Field Description	|
|:----|:--------------------|:--------------------:|:--------------------:|:--------------------|
|id| number| Id| The unique SEAD identification number.|
|sampledata_sample_name| number| Sampledata Sample Name| Name of the soil sample from which the data are derived, e.g. S2 for Sample 2.|
|sampledata_site_id| number| Sampledata Site Id| The unique number assigned to a particular collection site in the SEAD database. For online site landing page prefix this number with [https://browser.sead.se/site/](https://browser.sead.se/site/)|
|sampledata_dating_type| string| Sampledata Dating Type| Broad dating method type used to date sample.|
|sampledata_sample_group_id| number| Sampledata Sample Group Id| Identification number for the sample group.|
|sampledata_start| begin| Sampledata Start| Earliest possible date specimens were deposited.|
|sampledata_site_name| string| Sampledata Site Name| Name for the collection site based on geographic place names or other name used for identifying its location.|
|country| string| Country| The country in which the sample(s) were taken.|
|sampledata_end| begin| Sampledata End| Latest possible date specimens were deposited.|
|indicators_wild| number| Indicators Wild| Indicates that the specimen is from a wild species.|
|indicators_domestic| number| Indicators Domestic| Indicates that the specimen is from domesticated species.|
|sampledata_age_name| string| Sampledata Age Name| Geological or archaeological/cultural time period.|
|sampledata_age_abbreviation| string| Sampledata Age Abbreviation| Abbreviation of the geological or archaeological/cultural time period.|
|indicators_marine_mammal| number| Indicators Marine Mammal| Indicates that the specimen is whale, dolphin, porpoise, or seal species.|
|indicators_marine_fish| number| Indicators Marine Fish| Indicates that the fish specimen is found in, or taken from the sea.|
|indicators_terrestrial| number| Indicators Terrestrial| Indicates that the specimen lived on land.|
|indicators_freshwater_fish| number| Indicators Freshwater Fish| Indicates that the fish specimen is found living in or taken from fresh water.|
|indicators_aquatic|number|Indicators Aquatic|Indicates that the specimen lived in water.|
|indicators_non_migratory_terrestrial| number| Indicators Non Migratory Terrestrial| A bird that lives on land and doesn't migrate.|
|indicators_sea_bird| number| Indicators Sea Bird| A bird that frequents the sea or coast.|
|indicators_fresh_water_migrant| number| Indicators Fresh Water Migrant| A bird that frequents fresh water such as ducks and geese.|
|indicators_on_fast_ice| number| Indicators On Fast Ice| Found on ice that extends out from the shore and is attached to it. Specifc to pinnipeds (seals, sea lions, walruses, etc.)|
|indicators_on_floe_ice| number| Indicators On Floe Ice| Found on large flat free mass of floating sea ice. Specifc to pinnipeds (seals, sea lions, walruses, etc.)|



