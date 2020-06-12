![Vera Institute of Justice Logo](vera-logo.png)

# City Police Department Data Directory 
The Vera Institute of Justice has compiled a spreadsheet containing links to official police datasets for 72 cities - the 50 largest cities in the country and the largest city in each state. City size was determined using official US Census population estimates for 2019. The directory aims to create a single, easily accessible platform to find information on how departments are operating, and give an overview of how readily policing data is available for departments across the country.

## Data 
The data file is available in [CSV format](PD_Data_Directory.csv) and as a [Google Sheet](https://docs.google.com/spreadsheets/d/1oKnKVzF56zZqQxnHHnzs0FOuqBluj11N20V3IkwtmFc/edit?usp=sharing). Each row corresponds to a city and provides links to data officially made available by that city's police department. Some city police departments share a jurisdiction with other law enforcement agencies (such as sheriff’s departments or university police departments) which are not accounted for in this resource. Therefore, policing data provided by the police department of a particular city may not capture the operations of all policing organizations in that locality. 

Links to four different types of data sources are provided (where found). Those four types of data and the [variables](Codebook.csv) pertaining to each are as follows: 

### Use of Force 

The variables related to Use of Force are:
* `uof_url`: link to report or raw data reporting instances in which force is used by police officers 
* `uof_shootings_only`: indicates those datasets which only report officer-involved shootings  
* `uof_coverage`: span of time covered by dataset 
* `uof_foia_requested` indicates whether the use of force policy is available in the [Use of Force Project](http://useofforceproject.org/).
* `uof_notes`: other relevant information about the dataset or availability of information through the police department. For example, other distinctions in qualifications for inclusion in the dataset. 

### Arrests 

The variables related to Arrests are: 
* `arr_url`: link to reports or raw data reporting arrests made by city police officers 
* `arr_coverage`: span of time covered by dataset 
* `arr_demographic`: indicates whether the dataset includes demographic data for each arrest 
* `arr_download`: indicates whether the data itself is able to be exported from the online interface 
* `arr_notes`: other relevant information about the dataset or availability of information through the police department 

### Crime 

The variables related to Crime are: 
* `crime_url`: link to reports or raw data reporting crime incidents 
* `crime_coverage`: span of time covered by dataset 
* `crime_download`: indicates whether the data itself is able to be exported from the online interface 
* `crime_notes`: other relevant information about the dataset or availability of information through the police department 
* `map_url`: link to geographic visualization reporting crime incidents 
* `map_coverage`: span of time covered by dataset 
* `map_download`: indicates whether the data itself is able to be exported from the online interface 
* `map_notes`: other relevant information about the dataset or availability of information through the police department 

### Calls for Service 

Note: Since not all calls for service are indicative of crime and not all crimes are reported via 911, these data sources are distinct from crime (incident) data sources. 

The variables related to Calls for Service are: 
* `cfs_url`: link to reports or raw data reporting calls for service 
* `cfs_coverage`: span of time covered by dataset 
* `cfs_download`: indicates whether the data itself is able to be exported from the online interface 
* `cfs_officer_initiated`: indicates whether the dataset captures interactions initiated by officers (such as traffic stops, street investigations, observing crimes in progress, etc)
* `cfs_dispatched`: indicates whether the dataset includes only cases in which an officer was dispatched 
* `cfs_outcome`: indicates whether the dataset includes the outcome of each call for service 
* `cfs_location`: indicates whether the dataset includes location data for each call for service 
* `cfs_notes`: other relevant information about the dataset or availability of information through the police department 

### Population 

Population data can be important to understand the impact of police activity. Variables taken from official US Census Bureau population data are included in the spreadsheet for ease of reference.

The variables related to Population are: 
* `cens_pop_2010`: city population as actually measured on April 1, 2010 in the 2010 US Census
* `cens_est_base`: the base city population estimate as of April 1, 2010 used by the Census Bureau in later population estimates
* `cens_est_2010`: city population on July 1, 2010 as estimated by the Census Bureau
* `cens_est_2011`: city population on July 1, 2011 as estimated by the Census Bureau
* `cens_est_2012`: city population on July 1, 2012 as estimated by the Census Bureau
* `cens_est_2013`: city population on July 1, 2013 as estimated by the Census Bureau
* `cens_est_2014`: city population on July 1, 2014 as estimated by the Census Bureau
* `cens_est_2015`: city population on July 1, 2015 as estimated by the Census Bureau
* `cens_est_2016`: city population on July 1, 2016 as estimated by the Census Bureau
* `cens_est_2017`: city population on July 1, 2017 as estimated by the Census Bureau
* `cens_est_2018`: city population on July 1, 2018 as estimated by the Census Bureau
* `cens_est_2019`: city population on July 1, 2019 as estimated by the Census Bureau

## A Collaborative Resource 

Vera welcomes help filling gaps in the spreadsheet. To search for missing datasets, use a search engine or visit your local open-data portal or police department website to review available datasets. Use search terms such as “arrest data,” “911 calls for service data,” “crime incident data,” and “use of force data.” If you find official datasets to add to Vera’s spreadsheet, please email the links to ArrestTrends@vera.org. 

Vera recognizes that national policing data provided by other online sources can provide meaningful context to the exploration of the city policing data provided in this spreadsheet. Therefore, Vera has assembled a small list of national policing data sources - find those links [here](National_Policing_Datasources.csv). Vera welcomes additions to this list. If you find another public data source to add to this list, please email ArrestTrends@vera.org.  

These resources will be updated regularly to reflect the most recent contributions, and may include the introduction of new variables and data source types. 

## Acknowledgement 

In acknowledgement of the effort put forth to assemble this resource and in an effort to make this resource available to all interested parties, please credit https://github.com/vera-institute when using this resource. 

## Endmatter 

If you have further questions, please contact us at ArrestTrends@vera.org. 

The Vera Institute of Justice is a justice reform change agent. Vera produces ideas, analysis, and research that inspire change in the systems people rely upon for safety and justice, and works in close partnership with government and civic leaders to implement it. Vera is currently pursuing core priorities of ending the misuse of jails, transforming conditions of confinement, and ensuring that justice systems more effectively serve America’s increasingly diverse communities. For more information, visit www.vera.org.
