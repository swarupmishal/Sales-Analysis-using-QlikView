# Northwind Sales Analysis using QlikView
![alt text](https://github.com/swarupmishal/Sales-Analysis-using-QlikView/blob/master/Extras/sales-forecasting-250x250.jpg)

The purpose of the project is to understand all the functionalities of QlikView.


## What exactly the Data is? How can one obtain the Data?
The data is about the Sales of a Company. The data is already present in the Data folder. I have acquired data from various sources like excel, microsoft access and xml.

## Implementation:
Here I have tried to make use to all the important functionalities provided by QlikView. I have,
1. Used Dimensions and Measures
2. Loaded Fact table
3. Removed synthetic keys
4. Resolved circular loops
5. Generated data in the script
6. Used Mapping tables
7. Added Preceding load to the script
8. Loaded data from cross table
9. Created master calendar
10. Created link table
11. Handled slowly changing dimensions using IntervalMatch function
12. Made use of set analysis and aggregate functions
13. Loaded data from QVDs
14. Added Metadata and Section Access for Security

Because of the section access we have implemented, to open the app Northwind Sales.qvw we will have to login with either of the 3 USERIDs,
1.  USERID- ADMIN
    
    PASSWORD- PASS
    
    ADMIN has got all access.
2.  USERID- USER1
    
    PASSWORD- PASS1
    
    USER1 can only see data of USA and UK. USER1 has no access to City.
3.  USERID- USER2
    
    PASSWORD- PASS2
    
    USER2 can only see data for UK.
    
