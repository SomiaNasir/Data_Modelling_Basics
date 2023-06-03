# Data Modelling 
To understand how data modelling works, this repo covers designing the basic relational database schema in Python.

## Data Source
[Chinook Data](https://github.com/w3c/csvw/tree/gh-pages/examples/tests/scenarios/chinook) [accessed on 02-June-2023]  
This data source provides the csv files for all the tables in our database which can be used to read the data and populate the database. The following ER Diagram is helpful in developing the tables and defining the relations between them.
![image](https://github.com/SomiaNasir/Data_Modelling_Basics/assets/125132307/cd54b718-0b48-4bfe-8a3b-51b8df1208b0)

## Data Modelling
Google Colab for Python and SQLite databases were used for this task.  
[data_modelling_basics.py](https://github.com/SomiaNasir/Data_Modelling_Basics/blob/main/data_modelling_basics.py) contains the Python code for creating the database, creating the tables, establishing relationships between them and inserting the data from csv files into the database.
## Verfication using ER Diagram
After the successful creation of SQLite database, the ER diagram of the database can be made using MySQL Workbench. The step by step guide is illustrated in this [Guide](https://github.com/SomiaNasir/Data_Modelling_Basics/blob/main/creating_ER_diagram_guide.md). The following diagram is obtained which matches our original model from the beginning thus the schema is built correctly.  
![gg2](https://github.com/SomiaNasir/Data_Modelling_Basics/assets/125132307/ba32a6dc-ccac-475d-af58-8f018744f71a)
