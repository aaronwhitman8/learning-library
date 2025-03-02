# Introduction

## About This Workshop

This workshop covers how to load data in CSV files into the database and introduces key graph data modeling and analysis concepts and the interactive Graph Studio for working with graphs in an Autonomous Database. It shows you how to use graph queries to find circular payments which may indicate fraudulent transactions. You will load data from CSV files containing (artificial) Account and Transaction information. Then create a graph and finally query it and visualize the results.

Estimated Workshop Time: 60 minutes

### About Graph Studio
Oracle Autonomous Database has features that enable it to function as a scalable property graph database. They automate the creation of graph models and in-memory graphs from database tables. They include notebooks and developer APIs for executing graph queries using PGQL, a SQL-like graph query language, and over 60 built-in graph algorithms, and offer dozens of visualizations including native graph visualization.

Watch the following two videos for more information on Graph Studio. The first is an introduction to property graphs and their use cases. The second is a tour of the Graph Studio interface. 

[](youtube:eCd-969hrak)   Simplify Graph Analytics with Autonomous Database   

[](youtube:S6Q-IJcBkU0)   Autonomous Database: A tour of the Graph Studio interface

### Objectives

In this workshop you will:
* Connect to your autonomous database using SQLDeveloperWeb (aka Database Actions SQL) and load two CSV files
* Connect to your autonomous database using **Graph Studio**
* Create a graph using PGQL's (a graph query language) CREATE PROPERTY GRAPH statement
* Load the graph into memory for analysis
* Create a notebook
* Query and visualize the graph using PGQL notebook paragraphs
 
### Prerequisites

* Oracle Cloud Account
* Provisioned Autonomous Database-Shared instance
* A database user with the correct roles and privileges for working with **Graph Studio**. That is, successful completion of Lab 1 of the [Get Started with Graph Studio  workshop](https://oracle.github.io/learning-library/data-management-library/autonomous-database/shared/adb-graph/workshops/freetier/index.html?lab=lab-1-create-graph-user)  
  
  

## Acknowledgements
* **Author** - Jayant Sharma, Product Management
* **Contributors** -  Jayant Sharma, Product Management
* **Last Updated By/Date** - Jayant Sharma, April 2021


