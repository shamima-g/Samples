# Samples
# Automate lead management with Excel
This template integrates Excel data with Salesforce to ensure that while users continue capturing leads using their preferred tool.  This template serves as a foundation for creating Leads in Salesforce as Leads are updated and created in Excel Sheet. 

# Automate lead management with GoogleSheets
Business today demands up-to-the-minute data. Latency requirements are shrinking at the same time.  Sales use different tools to capture various information easily and quickly.
This template integrates GoogleSheet data with Salesforce to ensure that users continue capturing leads using their preferred tool.  This template serves as a foundation for creating Leads in Salesforce as Leads are updated and created in GoogleSheet.  This integration saves time by copying and pasting data from Googlesheet into Salesforce.

# Salesforce and Database Synchronization
Migrating data to and from Salesforce can be challenging due to data inconsistencies, invalid mapping, or improper formatting.
This template synchronizes products data between Salesforce and a database system like SQL Server. This template makes it fast to configure the fields to be synchronized, how they map, and criteria on when to trigger the synchronization.  This template imports products from the existing database into Salesforce and updates the product table in SQL Server with the salesforce ID.

# Automated account management with Bulk Data Process
The movement of large quantities of data is necessary during daily data sync.
This template upload account records that are stored in CSV format to Salesforce.  It uses the Bulk Api from salesforce.  It also verifies the job status and writes the result to a log file. 
 
### The template processes data in the following order;
1.	Create a new job that specifies the object and action.
2.	Send data to the server.
3.	Once all data has been submitted, close the job. Once closed, no more batches can be sent as part of the job.
4.	Check status. 
5.	Save the result sets with the original data set in a file, to determine which records failed and succeeded.
