# Big-Data-Project
Big Data Class Project 

CIS 4130 
Machine Learning Semester Project

Here is the link to the dataset that I have chosen to work with. 
https://data.cityofnewyork.us/City-Government/Open-Parking-and-Camera-Violations/nc67-uf89

I have chosen this dataset, as I recently received a traffic violation through the mail, that a camera had caught me in camera. Surprisingly, I haven’t received one yet, but just in my city they have been installing these cameras all over the place! The data set that I have chosen is about 22GB.s large. If necessary, I will have to filter out the information to create it to a more suitable size, with the professor's advice. 
Initially this dataset had been loaded onto the NYC OpenData database dated back to 2016. As of May 2016, the dataset “Open Parking and Camera Violations” is contained and updated continuously. As new violations are being issued, existing violations updated the dataset are also updated as well. Whether it is a new or an open violation the dataset is being updated weekly on Sunday. When a violation is satisfied then it has been paid for or dismissed via a hearing, statutorily expired or had other changes to its status, will be updated daily from the days Tuesdays through Sunday. Any violations that have been written off because of it being expired or no longer valid are indicated with blank financials. There is a summons column where we can visually see the summons, but the images will not be available on Sundays from 5am to 10am. The dataset is provided by data from the Department of Finance. Last known day to be updated, last day that I checked on the dataset on September 7th 2022. 
In total there are 85.5M rows and 19 columns. Each row shows the open parking and camera violation that had been issued.  The columns that I will be working with will be: (Plate, State, License Type, Issue Date, Violation Time, Violation, Fine Amount, Penalty Amount, Interest Amount, Reduction Amount, Payment Amount, Amount Due, Precinct, County, Issuing Agency, Violation Status and Summons Image). 

What I will like to find: 
Out of the violations, what is the percentage of the violations that get written off? 
As mentioned above - if a row's financial amounts are blank then the issuance has been written off because of it being expired or no longer valid. 
Is there a correlation between the license type? 
Is there a correlation in the time that a violation is being issued? 
What violations are most common, least common? 
Is there a correlation with the counties and the violations they issue? Is there a prominent issue between a county and violations?  
Is there a correlation with the issuing agency and the violations they issue? 
Is there a correlation with the State Plate and the violations issued? Do non-residents have a tendency for a violation? 
