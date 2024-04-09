# Welcome to My Ds Babel
***

## Task
What is the problem? And where is the challenge?
In this project we have to write two custum functions that will perform format conversions.
The first function should be able to take a file on sql formart and convert it to csv file. 
The second function take a csv file and convert it to sql file format. 

The main challenges in this project is to master sql querries and know how to connect to a 
sql database using python. 

## Description
How have you solved the problem?
To solve the problem I locate a time to learn how to connect to a sqlite database using python 
and how to write and execute sqlite's querries from my python code. 

Turning to the technical part of this question, for the first function `sql_to_csv(database,table_name)`
we connect to the database , write a querry to select all the information in it and then stored them in a 
pandas dataframe. We then converte the pandas dataframe to csv.
For the second function, we convert the csv file to an StringIO following the csv format and retrive all the 
data into list of list format where is list inside the main liste represent a row of data. 
Finaly , we create a databe using python and fill it by adding each observation row by row.
## Installation
How to install your project? npm install? make? make re?
None , we don't install anything

## Usage
How does it work?
To use , you juste need to run the main function
```
./my_project argument1 argument2
```

### Judicael Mahoutin DJIDONOU && Abdoul Razak ADAMOU


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>
