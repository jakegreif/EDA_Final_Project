# USGS Streamflow data for site 08057000


## Summary
This dataset was prepared for Jake Greif's final project for Environmental Data Analytics (ENV 872L) at Duke University, Spring 2019

The dataset contains streamflow data from the USGS streamflow gage site 08053000 (Elm Fork Trinity River near Lewisville, TX). 

## Database Information
Data were collected from the U.S. Geological Survey's Water Data website. More information can be found here: https://waterdata.usgs.gov/nwis

Data were collected using the Current Conditions tool on the USGS Water Data website (https://waterdata.usgs.gov/nwis).
From the Current Conditions homepage, the following selections were made: 
* Daily Stage and Streamflow (Predefined displays drop-down menu)
* Elm Fk Trinity Rv (station name)
* 08053000 (link on list)
* Select discharge (check boxes)
* Begin date: 1949-03-01 (begin date)
* End date: 2019-04-04 (end date)
* Tab separated (radio button)

csv file was saved as `USGS_Site08053000_Flow_Raw.csv`. 

Data were accessed 2019-04-05.

## Data Content Information 
Gathered from waterdata.usgs.gov:
 ---------------------------------- WARNING ----------------------------------------
 Some of the data that you have obtained from this U.S. Geological Survey database
 may not have received Director's approval. Any such data values are qualified
 as provisional and are subject to revision. Provisional data are released on the
 condition that neither the USGS nor the United States Government may be held liable
 for any damages resulting from its use.

 Additional info: https://help.waterdata.usgs.gov/policies/provisional-data-statement

 File-format description:  https://help.waterdata.usgs.gov/faq/about-tab-delimited-output
 Automated-retrieval info: https://help.waterdata.usgs.gov/faq/automated-retrievals

 Contact:   gs-w_support_nwisweb@usgs.gov
 retrieved: 2019-04-05 15:09:46 EDT       (vaww01)

 Data for the following 1 site(s) are contained in this file
    USGS 08053000 Elm Fk Trinity Rv nr Lewisville, TX

 Data provided for site 08053000
            TS   parameter     statistic     Description
        133457       00060     00001     Discharge, cubic feet per second (Maximum)
        133458       00060     00002     Discharge, cubic feet per second (Minimum)
        133459       00060     00003     Discharge, cubic feet per second (Mean)

 Data-value qualification codes included in this output:
        
     A  Approved for publication -- Processing and review completed.
     P  Provisional data subject to revision.
     e  Value has been estimated.

## Naming conventions and file formats
Files are named according to the following naming convention: `databasename_datatype_details_stage.format`, where: 

**databasename** refers to the database from where the data originated

**datatype** is a description of data 

**details** are additional descriptive details, particularly important for processed data 

**stage**refers to the stage in data management pipelines (e.g., raw, cleaned, or processed)

**format** is a non-proprietary file format (e.g., .csv, .txt)

## Additional Information and Support
For more information, please contact the data assembler, **Jake Greif** (jacob.greif@duke.edu)