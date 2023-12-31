# Key Database Queries for Administrators.

 A comprehensive guide to essential SQL queries that every database administrator should master for efficient database management and optimization.

SQL (Structured Query Language) is the Universal language of data. Now while considering the topic Mastering SQL, it is a life-changing skill that empowers individuals and organizations to hitch up the full potential of their data. Now let's explore what it really means to master SQL.
Before initiating with the technical stuff let’s explore the most important and useful queries.

### Back and Restore Queries

Backup queries are used for the protection of data. This query creates an extra copy of the available data in order to safeguard the data against data loss. This failure of data can be caused due to hardware failure, errors o disasters.



<Image src="/Website/public/blog2image1.png" width="718" height="404" alt="Image" />

On the other hand, a restore query is used to recover the database from the backups. Restore query ensures the data availability and minimizes downtime in case of data loss or system issues.

<Image src="/Website/public/b2image2.png" width="718" height="404" alt="Image" />

Backup and Restore queries become vital for database management, once the database is ready to bear with all the necessary operations.

Now to learn about the most basic query in SQL, I used a SELECT query which is also called as Data Retrieval query.

### Data Retrieval Query

For extracting specific information from a database, the data retrieval or SELECT query is used. The data retrieval queries allow searching, filtering, and retrieval of data based on various criteria. This enables users to access and analyze the data they need which can be used for reporting, analysis, or other applications.


<Image src="/Website/public/b2image3.png" width="718" height="404" alt="Image" />

SELECT query in SQL Server Management studio 2019 looks like this:
For example, we have a dataset which contains patient’s information.

<Image src="/Website/public/b2image4.png" width="718" height="404" alt="Image" />

In this query, the SELECT query is used to select the top 1000 rows of the dataset.

### Data modification queries

Mainly data modification queries are used to manage and manipulate data in SQL. These queries play a vital role in maintaining the accuracy and integrity of the database.

### Create query

The primary function of CREATE query in SQL is to create Tables which contain columns as an information. This query is used to populate data in the database depending on the relation of the columns. In SQL Server Management Studio 2019 this query looks like this:

<Image src="/Website/public/b2imnage5.png" width="718" height="404" alt="Image" />

This figure depicts that the ‘patient’ table is created using CREATE query and while creating the table, names and types of the columns are also defined.

### Insert query

For adding new records or rows of data into the table of the database, INSERT query is used. This query ensures that the new data entered in the columns is properly stored and can be manipulated when needed. INSERT query is important for populating the data.

<Image src="/Website/public/bgimage6.png" width="718" height="404" alt="Image" />

### Update query

This query is used for the modification of already existing records in the database. This query allows users to change the data in the columns ensuring that the data is updated to reflect new corrections and changes in the database. This query is crucial for the maintenance and accuracy of the data over time.
Let’s consider the example below, here we want to update the physician’s table. In this example, the ‘Specialization’ table is updated with the value ‘cardio’. But this query needs a condition for its execution which is ‘hospital’ value should be equal to ‘MH’.

<Image src="/Website/public/bg7.png" width="718" height="404" alt="Image" />

### Alter query

This query is used when the data in already created table needs to be altered. This query is mainly used for a slight change in already saved information. In the example below, ‘medical_record’ named table is altered. As it is mentioned that foreign key is defined in this process while including the reference key. A Reference key is the one which is a primary key in some other table and now will be recognized as a primary key in this table

<Image src="/Website/public/bg8.png" width="718" height="404" alt="Image" />

### Delete query

For removing specific records from the database DELETE query is used. Incorrect, outdated, or no longer needed data can be eliminated by the use of a DELETE query. This query is important for data maintenance to keep the database free from unnecessary data.

### Relationships

To show a connection between the tables, relationships are used. These relationships show Functional dependencies. In SQL Server Management Studio 2019, relation between the three tables namely, patient, medical_record and physicians are shown. The relation established is ‘One-to-many’.

<Image src="/Website/public/bg8.png" width="718" height="404" alt="Image" />

### Data integrity constraints

These are the safety checks in the database system. These are used to make sure that the data is accurate, consistent, and follows the rules you have set. It keeps checking the relationships between the columns. This ensures that your information is reliable.
In the figure below, ‘all_attributes’ table contains many columns which have their own predefined protocols. These protocols were assigned to these columns when the table was created or altered.

<Image src="/Website/public/bg10.png" width="718" height="404" alt="Image" />

Let’s discuss some other important topics which are a part of SQL.

### Security queries

SECURITY query in SQL is used to safeguard the data by creating, managing, and controlling user access and permissions within the database system. This query is used to monitor the activities of the database to ensure a secure database environment.

### Index optimization

This plays a role in enhancing the performance of queries in a database system. Indexes are the data structures that provide fast access to the records within the database. Creating, maintaining, and selecting correct indexes to increase the execution time within large data sets is called as Optimizing Indexes. This optimization will increase the performance of the overall database.

### Performance tuning

This is used to make your database work faster and more efficiently. It focuses on both performance and response rate. It involves making adjustments to the database so that it can handle more data and respond faster. This provides a better user experience and helps the application run smoothly.

### Database schema change

It is a process to make sure that the database can store and manage data to ensure the needs of your application or business plan. This can involve adding new storage spaces to your database. The modification queries are used in this process as well. It is like remodeling the house to arrange new furniture.

### Replication and clustering management

@@These terms in SQL, involve maintaining duplicate copies of your database or clustering of servers to enhance the availability and fault tolerance.
