# About dbdoc
dbdoc is a browser based application that fetches metadata of a database and shows it on screen in a tree structure. 

When a node (database, tables, views, functions, procedures etc.) shown in the tree is right-clicked, a popup window opens up for the user to add / edit / view description of the node.

The tree structure can be stored, along with the user-feeded description for different database entities and relationships, in a database (Postgres) in jsonb format and retrieved at a later stage to show in the tree structure as usual.

# Features
- Extract database metadata and display in a tree like structure
- User can add description to entities and relationships
- Save database metadata along with description in a separate database in jsonb format
- Generate and view graph database for the metadata in neo4j
- Generate and view network diagram
- Generate and view Entity-Relationship (ER) diagram
- Generate and download metadata documentation in MS Word format

# Limitations
As of now, dbdoc supports databases for Postgres, MySQL, MongoDB, MS SQL Server, Oracle, IBM DB2

# Preview
<img width="1822" height="882" alt="pic1" src="https://github.com/user-attachments/assets/abed4f0f-c0b5-43d8-812a-ef0bddb9501e" />

# Installation
Pre-requistes: You must have docker desktop installed.

dbdoc is installed in docker. Please download the dbdoc manual from the below link and follow the procedures.

[dbdoc-manual.pdf](https://github.com/user-attachments/files/22871272/dbdoc-manual.pdf)
