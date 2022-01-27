![Vera Institute of Justice Logo](vera-logo.png)

# City Police Department Data Directory 
The Vera Institute of Justice has compiled a spreadsheet containing links to official police datasets for 72 cities - the 50 largest cities in the country and the largest city in each state. City size was determined using official US Census population estimates for 2019. The directory aims to create a single, easily accessible platform to find information on how departments are operating, and give an overview of how readily policing data is available, for departments across the country.

## Data 
The data file is available in [CSV format](PD_Data_Directory.csv) and as a [Google Sheet](https://docs.google.com/spreadsheets/d/1oKnKVzF56zZqQxnHHnzs0FOuqBluj11N20V3IkwtmFc/edit?usp=sharing). Each row corresponds to a city and provides links to data officially made available by that city's police department. Some city police departments share a jurisdiction with other law enforcement agencies (such as sheriff’s departments or university police departments) which are not accounted for in this resource. Therefore, policing data provided by the police department of a particular city may not capture the operations of all policing organizations in that locality. 

Links to twelve different types of data sources are provided (where found). Those twelve types of data and the [variables](Codebook.csv) pertaining to each are as follows: 

### Use of Force 

The variables related to Use of Force are:
* `uof_url`: link to report or raw data reporting instances in which force is used by police officers 
* `uof_download`: indicates if the information contained in the URL link is downloadable
* `uof_freq`: indicates how frequently the data is updated
* `uof_data_type`: indicates how the data is structured (i.e. .csv, .pdf, report style)
* `uof_agg_type`: indicates if the data is captured at an incident level or an aggregate
* `uof_codebook`: indicates if a codebook is present for the data
* `uof_off_dem`: indicates if the dataset contains demographic information on the officer involved
* `uof_civ_dem`: indicates if the dataset contains demographic information on the civilian involved
* `uof_location`: indicates what location information is contained in the dataset (i.e. Address, Cross Streets, Latitude/Longitude) 
* `uof_embed`: indicates if there is internally embedded data analysis tools on the site page (i.e. mapping or charts with variable toggles)
* `uof_shootings_only`: indicates those datasets which only report officer-involved shootings 
* `uof_force_type`: indicates if the dataset contains use of force type
* `uof_justification`: indicates if the dataset contains use of force type   
* `uof_off_injury`: indicates if the dataset contains officer injury information
* `uof_civ_injury`: indicates if the dataset contains civilian injury information
* `uof_civ_weapon`: indicates if the dataset contains civilian weapon used information
* `uof_off_weapon`: indicates if the dataset contains officer weapon used information
* `uof_arrest_made`: indicates if the dataset contains if an arrest was made during the incident
* `uof_bodycam`: indicates if the dataset contains bodycam footage or data
* `uof_justification`: indicates if the dataset contains use of force type   
* `uof_coverage`: span of time covered by dataset 
* `uof_foia_requested` indicates whether the use of force policy is available in the [Use of Force Project](http://useofforceproject.org/).
* `uof_notes`: other relevant information about the dataset or availability of information through the police department. For example, other distinctions in qualifications for inclusion in the dataset. 

### Police Involved Shootings

The variables related to Police Involved Shootings are:
* `shooting_url`: link to report or raw data reporting instances in which police shot an individual
* `shooting_freq`: indicates how frequently the data is updated 
* `shooting_download`: indicates if the information contained in the URL link is downloadable
* `shooting_nonfatal_only`: indicates if the dataset only contains non-fatal shooting incidents
* `shooting_data_type`: indicates how the data is structured (i.e. .csv, .pdf, report style)
* `shooting_agg_type`: indicates if the data is captured at an incident level or an aggregate
* `shooting_codebook`: indicates if a codebook is present for the data
* `shooting_off_dem`: indicates if the dataset contains demographic information on the officer involved
* `shooting_civ_dem`: indicates if the dataset contains demographic information on the civilian involved
* `shooting_location`: indicates what location information is contained in the dataset (i.e. address, cross streets, longitude/latitude)
* `shooting_embed`: indicates if there is internally embedded data analysis tools on the site page (i.e. mapping or charts with variable toggles)
* `shooting_coverage`: span of time covered by dataset 
* `shooting_acc_discharge`: indicates if the dataset includes accidental firearm discharges
* `shooting_justification`: indicates if the dataset contains justification information
* `shooting_bodycam`: indicates if the dataset contains bodycam footage or information
* `shooting_notes`: other relevant information about the dataset or availability of information through the police department. For example, other distinctions in qualifications for inclusion in the dataset. 

### Arrests 

The variables related to Arrests are: 
* `arr_url`: link to reports or raw data reporting arrests made by city police officers 
* `arr_data_type`: indicates how the data is structured (i.e. .csv, .pdf, report style)
* `arr_freq`: indicates how frequently the data is updated
* `arr_agg_type`: indicates if the data is captured at an incident level or an aggregate
* `arr_codebook`: indicates if a codebook is present for the data
* `arr_off_dem`: indicates if the dataset contains demographic information on the officer involved
* `arr_arr_dem`: indicates if the dataset contains demographic information on the arrestee involved
* `arr_location`: indicates what location information is contained in the dataset
* `arr_embed`: indicates if there is internally embedded data analysis tools on the site page (i.e. mapping or charts with variable toggles)
* `arr_coverage`: span of time covered by dataset 
* `arr_demographic`: indicates whether the dataset includes demographic data for each arrest 
* `arr_download`: indicates if the data itself is able to be exported from the online interface
* `arr_charge`: indicates if the charge associated with the arrest was included
* `arr_uof`: indicates if force was used during the arrest event
* `arr_notes`: other relevant information about the dataset or availability of information through the police department 

### Calls for Service 

Note: Since not all calls for service are indicative of crime and not all crimes are reported via 911, these data sources are distinct from crime (incident) data sources. 

The variables related to Calls for Service are: 
* `cfs_url`: link to reports or raw data reporting calls for service
* `cfs_freq`: indicates how frequently the data is updated 
* `cfs_coverage`: span of time covered by dataset 
* `cfs_data_type`: indicates how the data is structured (i.e. .csv, .pdf, report style)
* `cfs_agg_type`: indicates if the data is captured at an incident level or an aggregate
* `cfs_timestamp`: indicates which timestamps exist
* `cfs_download`: indicates if the data itself is able to be exported from the online interface 
* `cfs_officer_initiated`: indicates if the dataset captures interactions initiated by officers (such as traffic stops, street investigations, observing crimes in progress, etc)
* `cfs_timstamps`: indicates if the dataset includes timstamps associated with the call (i.e. time created, time dispatched
* `cfs_dispatchedFlag`: indicates whether the dataset includes only cases in which an officer was dispatched 
* `cfs_calltype`: indicates if the dataset includes the call type (i.e. intial, final or general)
* `cfs_priority`: indicates if the dataset includes the call priority level
* `cfs_outcome`: indicates if the dataset includes the outcome of each call for service 
* `cfs_location`: indicates if the dataset includes location data for each call for service 
* `cfs_notes`: other relevant information about the dataset or availability of information through the police department 


### Crime 

The variables related to Crime are: 
* `crime_url`: link to reports or raw data reporting crime incidents
* `crime_freq`: indicates how frequently the data is updated 
* `crime_coverage`: span of time covered by dataset 
* `crime_data_type`: indicates how the data is structured (i.e. .csv, .pdf, report style)
* `crime_agg_type`: indicates if the data is captured at an incident level or an aggregate
* `crime_codebook`: indicates if a codebook is present for the data
* `crime_off_dem`: indicates if the dataset contains demographic information on the officer involved
* `crime_vic_dem`: indicates if the dataset contains demographic information on the victim involved
* `crime_acc_dem`: indicates if the dataset contains demographic information on the accused involved
* `crime_location`: indicates what location information is contained in the dataset
* `crime_embed`: indicates if there is internally embedded data analysis tools on the site page (i.e. mapping or charts with variable toggles)
* `crime_charge`: indicates if the dataset contains crime charge
* `crime_cleared`: indicates if the dataset contains if the crime was cleared 
* `crime_download`: indicates whether the data itself is able to be exported from the online interface 
* `crime_notes`: other relevant information about the dataset or availability of information through the police department 
 

### Crime Mapping

The variables related to Crime are: 
* `map_url`: link to reports or raw data reporting crime incidents
* `map_freq`: indicates how frequently the data is updated 
* `map_coverage`: span of time covered by dataset 
* `map_data_type`: indicates how the data is structured (i.e. .csv, .pdf, report style)
* `map_agg_type`: indicates if the data is captured at an incident level or an aggregate
* `map_location`: indicates what location information is contained in the dataset
* `map_embed`: indicates if there is internally embedded data analysis tools on the site page (i.e. mapping or charts with variable toggles)
* `map_download`: indicates whether the data itself is able to be exported from the online interface 
* `map_notes`: other relevant information about the dataset or availability of information through the police department 


### Traffic and Pedestrian Stops

The variables related to Traffic and Pedestrian Stops are: 
* `stops_url`: link to reports or raw data reporting arrests made by city police officers 
* `stops_data_type`: indicates how the data is structured (i.e. .csv, .pdf, report style)
* `stops_freq`: indicates how frequently the data is updated
* `stops_agg_type`: indicates if the data is captured at an incident level or an aggregate
* `stops_codebook`: indicates if a codebook is present for the data
* `stops_off_dem`: indicates if the dataset contains demographic information on the officer involved
* `stops_civ_dem`: indicates if the dataset contains demographic information on the civilian involved
* `stops_location`: indicates what location information is contained in the dataset
* `stops_embed`: indicates if there is internally embedded data analysis tools on the site page (i.e. mapping or charts with variable toggles)
* `stops_coverage`: span of time covered by dataset 
* `stops_demographic`: indicates if the dataset includes demographic data for each arrest 
* `stops_download`: indicates if the data itself is able to be exported from the online interface 
* `stops_notes`: other relevant information about the dataset or availability of information through the police department 


####Incoming Variables#####

* `stops_crime`:
* `stops_source`:
* `stops_frisk`:
* `stops_person_search`:
* `stops_vehicle_search`:
* `stops_reason`:
* `stops_search_result`:
* `stops_uof`:
* `stops_uof_reason`:
* `stops_removed`:
* `stops_outcome`:   

### Complaints and Police Misconduct

The variables related to Civilian Complaints and Officer Misconduct are: 
* `complaint_url`: link to reports or raw data reporting arrests made by city police officers 
* `complaint_data_type`: indicates how the data is structured (i.e. .csv, .pdf, report style)
* `complaint_freq`: indicates how frequently the data is updated
* `complaint_agg_type`: indicates if the data is captured at an incident level or an aggregate
* `complaint_codebook`: indicates if a codebook is present for the data
* `complaint_off_dem`: indicates if the dataset contains demographic information on the officer involved
* `complaint_arr_dem`: indicates if the dataset contains demographic information on the victim involved
* `complaint_location`: indicates what location information is contained in the dataset
* `complaint_embed`: indicates if there is internally embedded data analysis tools on the site page (i.e. mapping or charts with variable toggles)
* `complaint_coverage`: span of time covered by dataset 
* `complaint_demographic`: indicates whether the dataset includes demographic data for each arrest 
* `complaint_download`: indicates whether the data itself is able to be exported from the online interface 
* `complaint_notes`: other relevant information about the dataset or availability of information through the police department 

####Incoming Variables#####

* `complaints_int_ext`:
* `complaints_all_cat`:
* `complaints_allegation`:
* `complaints_timestamp`:
* `complaints_findings`:
* `complaints_disc`:
* `complaints_disposition`:
* `complaints_penalty`:
* `complaints_appeal`:
* `complaints_appeal_result`:


#### The  Following sets are generally non-numeric data

### Police Contact Information
* `police_contact_url`: link to pd contact information
* `police_contact_type`: indicated level of contact type (i.e. Main Office, Field Supervisor)
* `police_contact_notes`: other relevant information about the dataset or availability of information through the police department 

### Operations Manuals
* `ops_manual_url`: link to pd operations manual(s)
* `ops_manual_notes`: other relevant information about the dataset or availability of information through the police department 

### Training Materials
* `training_url`: link to pd training materials or guides
* `training_notes`: other relevant information about the dataset or availability of information through the police department 

### Use of Force Police
* `uof_policy_url`: link to internal pd use of force policy
* `uof_policy_notes`: other relevant information about the dataset or availability of information through the police department 

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
