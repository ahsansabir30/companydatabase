# CompanyDatabase
Company Database: includes tables, triggers, procedures (cursors), index and various select queries (to extract information from the tables)
Tables used in the database are as follow ...
  - Department
  - Employees
  - Employee Deletion 
  - Employee Names 

In the company database, i mainly used triggers to automate simple task such as
  - counting employees per department (and then updating the departments table)
  - calculating operation cost per department (in the database it is assumed to be employee salary)
 
If data values are changed within the database (such as a change in pay, new employees, or employees leaving) - the trigger will update the tables (right after deletion, update or insert of an new/old employee)  
