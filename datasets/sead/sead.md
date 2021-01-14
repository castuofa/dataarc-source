# Strategic Environmental Archaeology Database (SEAD)
**Creator:** Philip Buckland

**Description:** The Strategic Environmental Archaeology Database (SEAD) is a database of proxy evidence for past environments, climates and human activities. It makes data available from archaeological and geological excavations, and includes a range of fossil types as chemical and physical measurements from similar contexts. This feed to DataARC includes the environmental interpretation of fossil insect finds. Rather than presenting the raw data (in terms of numbers of individuals of the species found fossil), the dataset provides the meaning of the data in terms of the habitats which supported the species. In this way, the data can be more easily mapped to other data sources through common terms. The dataset includes the entire European fossil insect record, and stretches back to at least the last million years. Most of the data are, however, from the last few millennia.

**Publisher:** Umeå University, Sweden

**Contributor(s):** See original database for list of contributors - over 1400 publications [https://www.sead.se/](https://www.sead.se/)

**Created:** 2008

**DCMI Type:** collection

**Format:** JSON

**Language(s):** English

**Relation:** Buckland, P.I. & Buckland, P.C. (2006). BugsCEP Coleopteran Ecology Package. IGBP PAGES/World Data Center for Paleoclimatology Data Contribution Series # 2006-116. NOAA/NCDC Paleoclimatology Program, Boulder CO, USA. URL:http://www.ncdc.noaa.gov/paleo/insect.html or http://www.bugscep.com

**Subject(s):** ([FISH Vocabularies](http://www.heritage-standards.org.uk/fish-vocabularies/)) - 
[Archaeological Objects](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/ObjType_class.pdf): Insect Remains, Parasite Remains;
[Archaeological Sciences](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/ArchSci_class.pdf): Palaeoentomology, Palaeoenvironmental Analysis, Amino Acid Racemisation, Archaeomagnetism, Biostratigraphy, Dendrochronology, Electron Spin Resonance, Fission Track Analysis, Fluorine, Uranium And Nitrogen Tests, Lead Isotope Dating, Luminescence Dating, Mitochondrial DNA, Obsidian Hydration, Oxygen Isotope Analysis, Potassium Argon Dating, Radiocarbon Dating, Tephrochronology, Uranium Series Dating, Infra-red Stimulated Luminescence, Optically Stimulated Luminescence, Thermoluminescence, Microscopy, Beach Deposit, Geological Sediment, Peat Deposit, Flotation, Hand Retrieval, Coprolite, Pottery, Tufaceous Deposit, Impression;
[Events](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/Event_class.pdf):  Archaeological Intervention, Evaluation, Test Pit, Trial Trench, Underwater Evaluation, Excavation, Box Trenching, Open Area Excavation, Rescue Excavation, Research Excavation, Underwater Excavation, Grab Sampling, Environmental Intervention, Borehole Survey, Environmental Sampling, Core Sampling, Gravity Core, Vibro Core, Monolith Sampling, Casual Observation, Non Archaeological Intervention, Borehole Survey;
[Historic Characterization](http://www.heritage-standards.org.uk/wp-content/uploads/2020/02/HistoricCharacter_class.pdf): Aggregates Quarry, Ancient Enclosure, Ancient Woodland (Broadleaved), Ancient Woodland (Coniferous), Ancient Woodland (Mixed), Ancient Woodland (Replanted), Ancient Woodland, Barracks, Battlefield, Blanket Bog, Bog, Brickearth Pit, Canal, Carr, Carr, Castle, Castle, Cathedral, Cemetery, Chapel, Church, City, Clay Extraction Site, Clay Pit, Coastal And Intertidal, Coastal Wetland, Coastal Wetland, Copper Mine, Country Sport, Croft, Deer Park, Dunes, Dwelling, Enclosure Of Parkland, Extractive Industry, Farmstead, Field System, Fishing, Flash, Flood And Erosion Defence, Foreshore, Fortification, Freshwater Body, Funerary, Garden, Grassland, Groynes, Harbour, Health, Heathland, Hillfort, Hillfort, Historic Urban Core, Hospital, House, Infields, Inland Waterway, Isolated Dwelling, Isolated Farm, Lagoon, Lagoon, Lake, Managed Heritage Asset, Manor Farm, Manufacturing Industry, Market Place, Market, Marsh, Marsh, Marsh, Meadow, Mere, Military Residence, Mill Water System, Mill, Mine, Moorland, Moorland, Moorland, Mountain, Mudflat, Mudflat, Nucleated Settlement, Outfields, Palace, Palaeochannel, Palaeolandscape Component, Park, Peat Deposit, Peat Deposit, Peatland, Place Of Worship, Pond, Port And Dock Installation, Port, Processing Industry, Quarry, Raised Bog, Reclaimed Land, Religion, Residential Area, River, Road, Roman Fort, Roman Fort, Rough Ground, Royal Forest, Saltmarsh, Saltmarsh, Sandflats, Sea Defence, Shoals And Flats, Smallholding, Smallholding, Stone Quarry, Storage And Handling, Submerged Forest, Town Wall, Town, Upland, Valley Bog, Warehousing, Waste Disposal, Water Meadow, Water Transport, Watercourse, Wetland, Wood Pasture, Woodland (Broadleaved), Woodland (Coniferous), Woodland (Mixed)

**Extent, spatial:** Argentina, Austria, Belgium, Bermuda, Canada, Canary Islands, Channel Islands, Chile, China, Croatia, Czech Republic, Denmark, Egypt, England, Faroe Islands, Finland, France, Germany, Greece, Greenland, Hungary, Iceland, Iran, Iraq, Ireland, Israel, Italy, Japan, Latvia, Morocco, Netherlands, Norway, Oman, Peru, Poland, Russia, Scotland, Slovakia, Slovenia, Spain, Sudan, Sweden, Switzerland, Turkey, Ukraine, USA, Wales

**Extent, temporal:** 5,334,950 BCE-2,000 CE

**License:** CC BY

**Field List:**
| Field Name	| Field Type	| Field Title	| Field Description	|
|:----|:--------------------|:--------------------:|:--------------------|
|sead_id| number | Sead Id| The unique SEAD identification number|
|sead_country| string| Sead Country | The country in which the sample(s) were taken|
|sead_sampledata_site_id| number | Sead Sampledata Site Id| The unique number assigned to a particular collection site in the SEAD database. For online site landing page prefix this number with https://browser.sead.se/site/ |
|sead_sampledata_site_name | string| Sead Sampledata Site Name | Name for the collection site based on geographic place names or other name used for identifying its location |
|sead_sampledata_sample_name| string| Sead Sampledata Sample Name| Name of the soil sample from which the data are derived, e.g. S2 for Sample 2|
|sead_sampledata_sample_group_id| number| Sead Sampledata Sample Group Id | Identification number for the sample group|
|sead_sampledata_dating_type| string| Sead Sampledata Dating Type | Broad dating method type used to date sample|
|sead_sampledata_age_name| string| Sead Sampledata Age Name | Geological or archaeological/cultural time period|
|sead_sampledata_age_abbreviation| string| Sead Sampledata Age Abbreviation | Abbreviation of the geological or archaeological/cultural time period|
|sead_indicators_aquatics| number| Sead Indicators Aquatics | Insects living in/on water, in any form. From temporary pools to lakes and rivers.|
|sead_indicators_indicators_standing_water| number| Sead Indicators Indicators Standing Water | Insects with primary habitat in/on pools, ponds, slow flowing water – including temporary ponds, but not species specifically in vegetation and mud or banks of ponds|
|sead_indicators_indicators_running_water| number| Sead Indicators Indicators Running Water | Insects predominantly found in rivers and/or streams|
|sead_indicators_pasture_dung| number| Sead Indicators Pasture Dung | Insects indicating grazed land of varying form. Includes most dung beetles, including those that are not dependent on dung. Mostly open landscape, but may include pasture-woodland when in combination with woodland indicators|
|sead_indicators_meadowland| number| Sead Indicators Meadowland| Insects indicating natural grassland or near equivalents. Open landscape|
|sead_indicators_wood_and_trees| number| Sead Indicators Wood And Trees| Insect species tied to either the actual wood, trees or the forest/woodland environment. Generally shade tolerant|
|sead_indicators_indicators_deciduous| number| Sead Indicators Indicators Deciduous | Insects tied specifically to deciduous wood or woodland, species not found on coniferous wood except on rare occasions|
|sead_indicators_indicators_coniferous| number| Sead Indicators Indicators Coniferous | Insects tied specifically to coniferous wood or woodland, species not found on deciduous wood except on rare occasions|
|sead_indicators_wetlands_marshes| number| Sead Indicators Wetlands Marshes| Insects which are water tolerant but not living specifically in the water. May include mud and bank species, as well as those moss & reed dwellers that prefer permanently wet environments|
|sead_indicators_open_wet_habitats| number| Sead Indicators Open Wet Habitats|Insects with a preference for open, wet environments such as shingle, beaches etc. and other exposed wet environments |
|sead_indicators_disturbed_arable| number| Sead Indicators Disturbed Arable | Insects with a preference for any disturbed ground surface, be it disturbed by animal, geological or human action. Includes ploughed fields, edges of watering holes, farm yards, glacial margins etc.|
|sead_indicators_sandy_dry_disturbed_arable| number| Sead Indicators Sandy Dry Disturbed Arable | Insects with a preference for dry, disturbed environments. Typifies beach, dune and aeolian landscapes, or ploughed fields on more sandy soils. A more dominant environment in southern Europe than described by the Disturbed/arable indicator class|
|sead_indicators_dung_foul_habitats| number| Sead Indicators Dung Foul Habitats | A wide category for insect species that live in decaying, muddy and fetid environments, including compost, wet hay, dung and muddy edges of water|
|sead_indicators_carrion| number|  Sead Indicators Carrion  | End Insect indicators of animal carcasses of all forms, dry or wet. Generally forensically important species.|
|sead_indicators_indicators_dung| number| Sead Indicators Indicators Dung| Insects with primary habitat in dung, or dung essential for reproduction. Includes parasites of other species that live in dung. Majority of species not found in other environments represented by the broader dung/foul class, but some may be found on occasions outside of dung|
|sead_indicators_mould_beetles| number| Sead Indicators Mould Beetles | Insects associated with mold and decay, a large part of the typical indoor fauna associated with humans in northern Europe|
|sead_indicators_general_synanthropic| number| Sead Indicators General Synanthropic | Insects found in association with humans, either when outside of their ‘natural’ geographical range, or in all known records. This term may be geographically specific, and is used in a north European context here|
|sead_indicators_stored_grain_pest| number| Sead Indicators Stored Grain Pest | Pests of stored products, including grain, beans, sweetcorn etc. but also sometimes furs, meat and other animal material|
|sead_indicators_dry_dead_wood| number| Sead Indicators Dry Dead Wood| Insects associated with wood in constructions, but also similar natural environments such as large fallen trees, especially in warmer climates|
|sead_indicators_heathland_and_moorland| number| Sead Indicators Heathland And Moorland | Insects populating heathland and moorland, but may also indicate the under-story of a Boreal forest, which sometimes has similar vegetation|
|sead_indicators_halotolerant| number| Sead Indicators Halotolerant | Salt tolerant insects, often tied to coastal or salt marsh land, but not just NaCl (table salt) – can be species found on mineral rich ploughed soils or where mineral precipitation is prominent|
|sead_indicators_ectoparasite| number| Sead Indicators Ectoparasite | External parasites of humans and animals (includes many arthopods outside of the insect order)|
|sead_sampledata_start| number| Sead Sampledata Start | Oldest probable age of sample in years before AD1950 (BP)|
|sead_sampledata_end| number| Sead Sampledata End |Youngest probable age of sample in years before AD1950 (BP)|

