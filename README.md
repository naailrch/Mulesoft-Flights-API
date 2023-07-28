# myproject

This project represents a use case solution for the fictional Mule United Airport (MUA). United, Delta, and American Airlines have provided outgoing and incoming flight data to MUA in the form a RESTFUL web service, SOAP web service, and a MySQL database respectively. MUA also stores customer account information in both a MySQL database and Salesforce. 

This solution codes a multifunctional API that allows users to search data from all three airlines, either individually or combined, for a specific destination and stores their customer information in MUA's databases. In addition, a RESTful API had to be created and connected to the American Airlines SQL database to gain access to their flight data. Lastly, on-prem account data in MUA's SQL database was synchronized with Salesforce to create a backup of customer data stored that is accessible in a cloud service.
