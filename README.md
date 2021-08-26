# P1_Hive

## Project Description

This project aims to analyse movies data by using Apache Hive.

## Technologies Used

* Hortonworks Data Paltform - version 2.6.5
* Apache Hive - version 2.1.1

## Features

List of features ready and TODOs for future development
* movies which got most ratings.
* movies of specific genre.
* top rated movies.
* low rated movies. etc

To-do list:
* Partitioning and bucketing on tables
* More queries to be added

## Getting Started
   
1. Clone the project
```
$ git clone https://github.com/munjanichintan123/P1_Hive.git
```

## Usage

A Hadoop ecosystem
  * Apache Hadoop should be installed with all the components.

## Contributors

1. After logging into VM, clone the project onto local machine and unzip all the csv files.
2. Then, copy csv files from local to hdfs.
```
$ hdfs dfs -put ./filename <hdfs-path>
```
3. You can use hive using either hive shell or hive view. (Type hive to start hive shell)
4. Upload the data from all the csv files to the respective tables from Hive View->Upload Table
5. Then, start executing queries.
