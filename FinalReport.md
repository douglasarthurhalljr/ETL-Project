FINAL REPORT

Extract
- The original data sources we used were one (1) CSV file and one (1) sqlite file.
- Our sqlite file consisted of nba player data, including draft, salary, and bio data. 
- The CSV file consisted of additional nba player information.
- Our goal was to take these two separate data sources and extract and combine them using a non-relational database. 

Transform
- In order to prepare our data, it needed to be cleaned and joined via common pieces of data. 
- First, we cleaned our two data sets to eliminate null rows and improve the data set. We continued on to aggregating the two data sources by common columns and data types. 
- Next to test our newly joined data sets, we wrote fiter queries to test and display our newly transformed data.

Load
- The final production database for the data to be loaded into will be a non-relational database.
- The final tables or collections include two data sets. One with basic player infomation (name, position), sorted by last name. The second, which consists of draft infomation for the top ten draft picks each year dating back to 1949.
- We chose this database and these tables because we believe it was the most appropriate use of our data sets and displayed our data in the most useful and concise manner. 

