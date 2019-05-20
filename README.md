First Project wuth Udacity.

Exploring Weather Trends

Summary
In this project, you will analyze local and global temperature data and compare the temperature trends where you live to overall global temperature trends.

Extract the data form the database.
o Write a SQL query to extract the city level data. Export to CSV. 
o Write a SQL query to extract the global data. Export to CSV.  

 Solution:  
 Query to extract city level data:  SELECT *  FROM city_data  WHERE country = 'Saudi Arabia' And city = 'Riyadh'; 
 
 Query to extract global data:  SELECT *  FROM global_data; 
 
 Open up the CSV.  
Download the data based on filtering queries on city_data and global_data databases in Excel format in local computer. 
 
 Create a line chart. 
Since moving average are to be used to compare the city temperature with the global temperature, Average () function were used to calculate the results. Average were according to every 3 years. These values were saved in columns named ‘Riyadh_City_MA’ and ‘Global_MA’ in the file. 
