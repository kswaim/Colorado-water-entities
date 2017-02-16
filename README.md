# Colorado-water-entities
Dataset of municipalities, metro districts, water and sanitation districts and water conservancy districts in Colorado.

This dataset was created to understand the number of entities in Colorado that can be considered water users or water providers.  Currently, the dataset is a list of municipalities, metropolitan districts, water and sanitation districts, water conservancy districts, water authorities and water companies within Colorado.  The Open Water Foundation (OWF)'s first objective with this dataset is to create a unique ID for each entity.  Many of the entities have a local government ID that is used by the Colorado Department of Local Affairs (DOLA); they may also have a Public Water System ID that is used by the EPA.  However, there is no single ID that covers all of the entities listed here, thus the reason for creating a unique ID for each entity.

OWF envisions that this dataset may eventually contain data such as annual population totals for each entity and annual water use.

Data were downloaded in February 2017 from the Special Districts website from Colorado's State Demography Office:
https://demography.dola.colorado.gov/CO_SpecialDistrict/.
Data were downloaded as shapefiles for Metropolitan Districts, Water and Sanitation Districts and then All Districts to parse out the Water Conservancy Districts and Water Authorities.  The shapefiles were opened in QGIS and then the attribute tables saved as CSVs.  Data from the CSV files have been compiled into this dataset.

DOLA's Local Government Information System also has information about special districts:  https://dola.colorado.gov/lgis/.
Local government IDs (LGID) are provided from this website.  Note that municipalities also have a Local Government ID.

The Special Districts shapefiles were missing approximately 230 metro districts and 15 water conservancy districts.  Information from the Local Government Information System was used to add in the missing districts.  Therefore, the shapefiles are not complete datasets.

EPA data were downloaded from the following website:  https://ofmpub.epa.gov/apex/sfdw/f?p=108:1:::NO:::
This is the EPA's Safe Drinking Water Information System (SDWIS).  Each entity has a Public Water System (PWS) ID.  This is used for water quality reports.

Note that this dataset is not a complete list of all water entities, particularly water companies.
