# exploring_data_in_foster_care
* Ask the questions:
    * 1. What is the sum/avg of children placed in fostercare per state?
    * 2. What is the median household income per state?
    * 3. How many highschool dropouts per state?
    * 4. Is there a coorelation between these datasets?

* Gather the data:
    * 1. https://datacenter.aecf.org/data/tables/6242-children-ages-birth-to-17-in-foster-care?loc=1&loct=2#detailed/2/2-53/false/2048,574,1729,37,871,870,573,869,36,868/any/12985,20455
    * 2.  https://datacenter.aecf.org/data/tables/123-median-family-income-among-households-with-children-by-family-nativity?loc=1&loct=1#detailed/1/any/false/2048,1729,37,871,870,573,869,36,868,867/78,79/461 
    * 3. https://datacenter.aecf.org/data/tables/10439-youth-in-foster-care-who-graduated-high-school-on-time#detailed/2/any/false/1095,2048,574,1729,37,871/217,757,107,133,172,4/20134

* Assign roles
    * 1. Clayton Graves: Cheerleader, GitMaster, Coder, Data Analyst, Presenter
    * 2. Rodney Masarirambi: Data Analyst, Coder, Presenter
    * 3. Derek Rikke: Data Analyst, Coder, Presenter

* Pull the data in and clean it
    * 1. Read each csv in as a data frame
    * 2. Drop column LocationType
    * 3. Drop all rows with "United States" in Location column
    * 4. Rename Location to "State"
    * 5. Rename TimeFrame to "Year"
    * 6. Fill null values default text "N/A"