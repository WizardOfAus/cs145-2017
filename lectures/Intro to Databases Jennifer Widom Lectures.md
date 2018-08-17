# Intro To Databases

Databases handle data on a massive scale. Database management systems are:

* Massive - terabytes
* Persistent - data outlives the program
* Safe - data will remain in a consistent state regardless of hardware, software or power failures
* Multi-user - concurrency control; control how multiple users access the data items of the db
* Convenient - 'Physical Data Indepdence' (operations on data is independent from the program of the database). Make it easy to control large amount of data. High level query language (declarative) - you specify and don't need to think about the algorithm for the most efficient way to get the data out.
* Efficient - thousands of queries/updates per second
* Reliable - 99.999999..% 

Database applications may be programmed via "frameworks". Database Management Systems may run in conjunction with "middleware". Data-intensive applications may not use DBMS at all e.g. hadoop.

## Key Concepts

* Data model - set of records, XML, graph
* Schema versus data - i.e. Types versus Variables
* Data Definition Language (DDL) - set up schema
* Data Manipulation or Query Language (DML) - querying and modifying the db

## Key people

* DBMS implementer - builds system
* Database designer - establishes schema
* Database application developer - programs that operate on database
* Databse administrator - loads data, keeps it running smoothly
