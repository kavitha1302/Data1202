# First lab practice in github.

I am a student in Data Analytics 1202 and I am trying to use and learn Github.


## Getting Started

### Prerequisites

I have installed the below softwares for doing this lab,

MYSQL server 11 and anaconda 3

### Installing

Installation Steps:
MYSQL portable version:

1. Extract the my sql Folder from the Zip file

2. Run the Windows Batch File "MYSQL"

3. Enter Option 1 to start the server

4. Enter Option 3 to start MSQL workbench

5. Create a sql connection by giving user and port values.

Anaconda Installation:

1. Go to this Anaconda website for downloads - https://www.anaconda.com/products/individual 
2. Download the latest version of Anaconda (64-bit graphical installer for Python 3.8 version)
3. After the installation is completed,
a) On a Windows PC, from the start menu, select Anaconda3(64-bit), then select Anaconda
Navigator.
4. In homepage install Jupiter notebook

Python Libraries Install

5. Launch Command Prompt
a) Windows PC open the Anaconda Prompt (start menu under Anaconda3(64-bit))

6. Enter the following commands one at time and wait for each install to complete running.
 pip install plotly
 pip install imbalanced-learn
 pip install mlxtend
 pip install pandas-profiling
 pip install Boruta

## Lab Description

Steps for the Python code in the attached assignment#3 lab file,

##Step 1:
Imported pandas as pd 

##Step 2:
Instead of uploading the csv file we set the file path to a variable here.

##Step 3:
Here we tried to read the Data into a DataFrame.

##Step 4:
In this step imported pandas, sqlalchemy and pymysql libraries.

##Step 5:
Here we created a engine with mysql and pymysql

##Step 6:
Created a connection string.

##Step 7:
Tried to read a simple query in python.

##Step 8:
Printed the dataframe output by using df.head()

##Step 9:
##python example for the average of global sales higher before or after 2005.

After running the python code, we got the average global sales as 0.649 for the years which are less than 2005, 0.489 for the years after 2005 and 0.488 average global sales for the years in 2005. So from the above results, we can see that the global sales average value is higher for the years which are less than 2005.

##Step 10:## Create a new column that labels records before 2005 as 'pre-2005' and after 2005 as 'post-2005'.

After running the python code, we got a new column as ‘Label’ which shows the records for different years.
Here, we used the CASE function to label the data as ‘pre-2005’ when it falls under the year 2005 and ‘post-2005’ when it falls after the year 2005 in the label column. 

##Deployment

## Authors

* **Kavitha SC**

## License

This project is free to use.

## Acknowledgments

* Used the class assignment for this lab and the class materials for mysql server installation steps given by professor Omar Al-Trad in Data-1202. 
* Referred to Ade oridate class materials to represent the anaconda installation steps in Data-1200

