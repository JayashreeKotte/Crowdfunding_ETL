# Crowdfunding_ETL
## Project 2 - ETL Mini Project

ETL mini project is aimed at making using of Python, Pandas and either Python dictionary methods or regular expressions to extract and transform the data. <br>

Post transforming the data, extract data into flat files like csv files <br>

Four CSV files contaning all the data in different tables should be generated <br>

An Entity Relationship Diagram (ERD) and table schema must be created using the information in the CSV files <br>

Finally, the csv files must be uploaded into a Postgres database 

## How to Install and Run the code
1. Ensure _Resources_, _*SQL_files*_ and _Data_ folders are present in the ***Crowdfunding_ETL*** folder

2. Ensure files _*ETL_Mini_Project_JKotte.ipynb*_, _*contacts.xlsx*_ and _*crowdfunding.xlsx*_ files are present in the _Resources_ folder

3. The _Data_ folder contains all exported csv files after transforming the data 

4. The _*SQL_files*_ folder contains the _*CrowdFunding_DB_ERD.png*_ ERD image and _*crowdfunding_db_schema.sql*_ file to use in a Postgres database.

5. To run the code, you will need access to Jupyter Notebook, PostgreSQL and pgAdmin

6. Open Jupyter Notebook in the terminal or command prompt and run the entire _*ETL_Mini_Project_JKotte.ipynb*_ notebook in _Resources_ folder using the _"Restart & Run All"_ option from _*Kernel*_ dropdown.

7. Ensure everything runs successfully, check four csv files are created and added to the _Data_ folder.

8. Inspect the four csv files and create an ERD using QuickDBD application 

9. Post giving the table names, column names and connections in the QuickDBD application, export it as a PNG file _*CrowdFunding_DB_ERD.png*_ and a Postgres file (schema file) _*QuickDBD_schema.sql*_

10. Open pgAdmin, create a database with crowdfunding_db as the name 

11. Open the query tool for the above created DB

12. In the query tool window, open _*crowdfunding_db_schema.sql*_ file from _*SQL_files*_ folder and run the code

13. Run everything except the select statements to create the tables successfully.

14. Ensure the tables are created using SELECT sql statements in the file at the end

15. Additionally, you can always modify the sql file to add more queries and play around with it for desired results.

![Crowdfunding_DB](Crowdfunding_ETL/SQL_files/CrowdFunding_DB_ERD.png)

## Credits

To complete this challenge, I referred to previous pandas classes to get all the methods for accurate data transformation. Referred to different data traversal methods in a Panda DataFrame. Spoke to my TAs about data traversal and the ERD connections in QuickDBD.
My peers were very helpful in offering tiny hints to power through when I felt stuck. I also edited the original schema file from QuickDBD as there was error when trying to run it as is. Manually edited the schema file to make foreign key connections to different tables. 

## References

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.iterrows.html

https://app.quickdatabasediagrams.com/#/

https://www.dataquest.io/wp-content/uploads/2019/03/python-regular-expressions-cheat-sheet.pdf

https://regex101.com/

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.items.html

https://docs.python.org/3/library/re.html#module-re

https://docs.python.org/3/howto/regex.html#regex-howto

https://pandas.pydata.org/docs/reference/api/pandas.Series.str.extract.html









