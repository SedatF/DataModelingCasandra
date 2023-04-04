# Data Modeling with Casandra

A startup called Sparkify wants to analyze the data they collect about songs and user activity in the new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, as the data resides in a directory of CSV files for user activity in the app.

Purpose of this project is to create an Apache Cassandra database which can be used to query song play data to answer Sparkify's questions.

## Project Overview
In this project, I  applied what you've learned on data modeling with Apache Cassandra and complete an ETL pipeline using Python. To complete the project, I need to model your data by creating tables in Apache Cassandra to run queries. I provided with part of the ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

I have provided you with a project template that takes care of all the imports and provides a structure for ETL pipeline you'd need to process this data.

## Details of Data Model and Queries

Details of data model/queries are explained in IPython notebook.

## Note:

Provided CSV files reading code was not working properly. So, I changed that to following line to get all 6000+ rows from all csvs.
```file_path_list = glob.glob(os.path.join(filepath, '*'))```


