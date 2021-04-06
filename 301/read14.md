# Database Normalization
Database normalization is a process used to organize a database into tables and columns. The main idea with this is that a table should be about a specific topic and only supporting topics included.

By limiting a table to one purpose you reduce the number of duplicate data contained within your database. This eliminates some issues stemming from database modifications.

# Reasons
minimize duplicate data
minimize or avoid data modification issues
simplify queries
Data Duplication and Modification Anomalies
Duplicated information presents two problems:

increases storage and decrease performance.
becomes more difficult to maintain data changes.
To fix this There are three modification anomalies that can occur: Insert Anomaly There are facts we cannot record until we know information for the entire row her we specify a unique index for a row such as the ID. Update AnomalyIn this case we have the same information in several rows,then there are multiple updates that need to be made. If we don’t update all rows, then inconsistencies appear. Deletion AnomalyDeletion of a row causes removal of more than one set of facts.

# Search and Sort Issues
To make it easier to search and sort your data.You would have to use three separate UNION queries! You can eliminate or reduce these anomalies by separating the data into different tables. This puts the data into tables serving a single purpose. The process to redesign the table is database normalization. There are three common forms of database normalization: 1st, 2nd, and 3rd normal form. They are also abbreviated as 1NF, 2NF, and 3NF respectively.

First Normal Form – The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key.
Third Normal Form – the table is in second normal form and all of its columns are not transitively dependent on the primary key