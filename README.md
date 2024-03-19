# FirnAquifers_GRL
Firn aquifers probability _ data repository for GRL

Repository Description: Probability of Firn Aquifer Presence in Antarctica by Combining Remote Sensing and Regional Climate Model Data 
GRL, Di Biase et al., (2024)

Welcome to the repository containing files related to the GRL article "Probability of Firn Aquifer Presence in Antarctica by Combining Remote Sensing and Regional Climate Model Data."

Structure:
Data: Antarctica (AP) and Greenland

Each "Data" folder contains five files in .tif format, representing the output of Monte Carlo tests as described in Section 3 of the Letter.
S1
ascat
deltaDOY
melt
accumulation
Each file consists of five layers, one for each year from 2017 to 2021. The resolution is 2 km in the EPSG 3031 coordinate reference system for Antarctica and EPSG 4326 for Greenland.

Info:

The "Info" folder includes a file named Greenland_basins.jpg, representing Greenland's regions (source: http://imbie.org/imbie-3/drainage-basins/, last accessed: 27/02/2024) for reference.
**Code: Script_ASCAT_EndOfMeltSeason **

The code "Script_ASCAT_EndOfMeltSeason" contains the script that calculates the last day of melt based on ASCAT observations.
