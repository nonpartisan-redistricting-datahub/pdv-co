# vest-co-2018

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2018-washington-precinct-and-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.


#### VEST data

----

VEST data files include:  

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  **co_2018.shp** which has both election results and shapefiles, can be found [here](https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/UBKYRU/PPH2WE&version=36.0). 


The election data columns reported are:

<font color="Coral">
    

Secretary of State
    
    1. G18SOSRPAT - Paul D. Pate (Republican Party)
    2. G18SOSDDEJ - Deidre DeJear (Democratic Party)
    3. G18SOSLOFE - Jules Ofenbakh (Libertarian Party)
    4. G18SOSOWRI - Write-in Votes
    
Governor
    
    1. G18GOVRREY - Kim Reynolds (Republican Party)   
    2. G18GOVDHUB - Fred Hubbell (Democratic Party)
    3. G18GOVLPOR - Jake Porter (Libertarian Party)
    4. G18GOVOSIE - Gary Siegwarth (Clear Water Party)
    5. G18GOVOWRI - Write-in Votes
    
Attorney General
    
    1. G18ATGDMIL - Tom Miller (Democratic Party)
    2. G18ATGLBAT - Marco Battaglia (Libertarian Party)
    3. G18ATGOWRI - Write-in Votes

Treasurer
    
    1. G18TRERDAV - Jeremy N. Davis (Republican Party)
    2. G18TREDFIT - Michael L. Fitzgerald (Democratic Party)
    3. G18TRELHIR - Timothy Hird (Libertarian Party)
    4. G18TREOWRI - Write-in Votes

    
Auditor
    
    1. G18AUDRMOS - Mary Mosiman (Republican Party)
    2. G18AUDDSAN - Rob Sand (Democratic Party)
    3. G18AUDLPER - Fred Perryman (Libertarian Party)
    4. G18AUDOWRI - Write-in Votes
    

Agriculture Secretary
    
    1. G18AGRRNAI - Mike Naig (Republican Party)
    2. G18AGRDGAN - Tim Gannon (Democratic Party)
    3. G18AGRLSTE - Rick Stewart (Libertarian Party)
    4. G18AGROWRI - Write-in Votes

</font>

#### Raw shapefile data

----

The following counties were reached out to directly for precinct shapefile data. 

Each county used unique data formats, but all of the relevant files can be found in **<font color="Coral"> raw-from-source/county_download/{county name all lowercase}</font>**

- **Adams** - data found [here](https://data-adcogov.opendata.arcgis.com/search?q=precinct)

- **Arapahoe** - data found [here](https://www.arapahoegov.com/1151/GIS-Data-Download)
 

- **Boulder** - data found [here](https://opendata-bouldercounty.hub.arcgis.com/datasets/precincts?geometry=-106.243%2C39.904%2C-104.503%2C40.272)

- **Delta** - requested data by emailing gis@deltacounty.com, will package shape files and send to us. Email with shapefiles received from Carrie Derco, GIS coordinator for Delta County.

- **Denver** - data found [here](https://www.denvergov.org/opendata/dataset/city-and-county-of-denver-election-precincts)

- **Douglas** - data found [here](https://hub.arcgis.com/datasets/dougco::voter-precincts-1?geometry=-106.172%2C39.162%2C-103.814%2C39.533) 

- **El Paso** - received shapefiles from email via GIS director Dwayne Liller (DwayneLiller@elpasoco.com)


- **Fremont** - data found [here](https://www.fremontco.com/clerk-and-recorder/elections)

- **Garfield** - Update to precinct boundaries explained [here](https://www.garfield-county.com/news/clerk-recorder-2017-precinct-boundaries/). shapefiles received by email from GIS coordinator Andrea Grygo (agrygo@garfield-county.com)

- **Gilpin** - shapefiles received via email from County Planner Tami Archer, (tarcher@gilpincounty.org) 

- **Jefferson** - data found [here](https://data-jeffersoncounty.opendata.arcgis.com/datasets/county-precinct-1?geometry=-107.581%2C39.151%2C-102.865%2C39.893)

- **La Plata** - data found [here](https://www.co.laplata.co.us/services/elections/index.php)

- **Larimer** - data found [here](https://www.larimer.org/it/services/gis/digital-data)

- **Mesa** - data found [here](https://opendata-mesacounty.hub.arcgis.com/datasets/7dd0dcebc31944ba8eea467c997c3829_15?geometry=-110.582%2C38.559%2C-105.866%2C39.307)

- **Pitkin** - data found [here](https://pitkincounty.com/874/Base-Map)

- **Pueblo** - requested data from edgis@pueblocounty.us., shapefiles received from Robert Deherrera (robde@pueblocounty.us) 
 
- **Summit** - data found [here](https://data-summitcountyco.opendata.arcgis.com/search?groupIds=548c92e5e1af41a09155d6ff7141fba0)

- **Weld** - data found [here](https://gishub.weldgov.com/datasets/7205d33baa7d48d285bf08c5e9803213_0?geometry=-106.670%2C40.137%2C-101.954%2C40.867)

##### The remaining counties were taken from the Census Phase 2 data, downloaded from [this link](https://www.census.gov/geo/partnerships/pvs/partnership19v2/st08_co.html). 




#### Raw election results data

----

- Most election results were pulled from the [SoS website]
(https://www.sos.state.co.us/pubs/elections/Results/archive2000.html), 
   

- All of the data for CO accessed and downloaded between the dates of April 12th and April 16th, 2021. 

## File processing:

- `VEST-co-2018-validation.ipynb` - documentation within comments and markdown cells
