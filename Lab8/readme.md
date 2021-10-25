## VIKTORYIA GIDREVICH/ 10.24.21

## Executive Summary 
In this unit, we learn about Data Analytics, Ethical and Legal Implications. I liked to try myself at SQL. It was so exciting like Python. I got a lot of useful sources where I can find everything about Ethical and Legal Implications.

## Data, Information and Knowledge
### Compare and contrast data, information and knowledge
Information (Lat. informatio) - 1) a message about something; 2) information that is the object of storage, processing and transmission (for example, genetic information); 3) in mathematics (cybernetics) - a quantitative measure of eliminating uncertainty (entropy), a measure of system organization; in information theory - a section of cybernetics that studies quantitative patterns associated with the collection, transmission, transformation and calculation of information.
Data - 1) information necessary for any conclusion, decision, procedure (for example: a lot of data, digital data); 2) grounds for something, quality (for example: voice data, have all the data to receive a prize).
Knowledge - 1) comprehension of reality by consciousness, science (for example: an important field of knowledge, craving for knowledge); 2) a set of information, knowledge in any field (for example: a field of knowledge, craving for knowledge).
The concept of "information" is more closely related to the essence of processes in information systems, while the concept of "knowledge" is related to the quality of processes in information systems.


### Relational Data
#### Primary Key:
In our example, we have a table of student data, with each row representing a student record , and each column representing one filed of the student record.   A special filed or a combination of fields that determines the unique record is called primary key (or key).  A key is usually the unique identification number of the records.

#### Relationship between customers and orders:
A relationship between two tables is implemented by using a foreign key.  The Customers table holds a unique record for each customer. Each customer can (and, we hope, does) place many orders. Many records in the Orders table can relate to only one record in the Customers table. This is a one-to-many relationship (1:N) between the Customers table and the Orders table.

#### Foreign key of orders table:
A foreign key is a field in one table that connects to the primary key data in the original table.  The "PersonID" column in the "Orders" table is a FOREIGN KEY in the "Orders" table. The FOREIGN KEY constraint prevents invalid data from being inserted into the foreign key column, because it has to be one of the values contained in the parent table.
### Field Data Types

### Big Data
The properties of the field describe the characteristics and behavior of the data being added to it. The data type of a field is the most important property that determines what data can be stored in the field.
There are two important reasons why we need to correctly determine the data type of the field. First, the data type tells the database what functions can be performed with the data. For example, if we want to perform mathematical functions with one of the fields, we must necessarily inform the database that this field is a numeric data type. For example, we can subtract the course capacity from the classroom capacity to find out the number of additional seats available.

The second important reason for determining the data type is to ensure that the proper amount of disk space is allocated for our data. For example, if the studentName field is defined as the Text (50) data type, this means that 50 characters are allocated for each name we want to save. If the student's name is longer than 50 characters, the database will truncate it.

#### Four "V"s of Big Data
Advantages of Big Data:
•	Companies can use external intelligence when making decisions
•	Improved customer service
•	Early identification of product/service risk, if any
•	Better operational efficiency

#### Technology Driving the need for Big Data
Definition of big data: Big data means huge data. Bigdata is a term used to describe a huge data set that nevertheless grows exponentially over time.
Examples of big data analytics include stock exchanges, social networking sites, jet engines


## Structured Query Language (SQL) 
### RDBMS and SQL
RDBMS and SQLRDBMS stands for Relational Database M BOARD System. DBMS is the basis for SQL.
A Relational Database Management System (DBMS) is a database management system (DBMS) based on the relational model presented by EF Codd.
The data in the DBMS is stored in database objects called tables. This table is basically a set of related data records and consists of many columns and rows.

### Relationship, Primary and Foreign Keys
A foreign key is a column or set of columns in one table that reference primary key Ccolumns in another table. The primary key is defined as a column (or set of columns) where each value is unique and identifies one row of the table.

## SQL Injections
SQL injection is one of the most commonly used vectors of web attacks used to obtain confidential data from organizations. When we hear about stolen credit cards or password lists, it's often because of SQL injection vulnerabilities. Fortunately, there are ways to protect the site from attacks using SQL injections.
To protect the website from SQL injection, we can use SQL parameters.
SQL parameters are values that are added to an SQL query at runtime in a controlled manner.


## Ethical and Legal Implications
### Code of Ethics
The Code is intended to inspire and guide the ethical behavior of all professionals in the field of computing, including current and novice practitioners, teachers, students, influencers and anyone who effectively uses computing technologies. In addition, the Code serves as a basis for correcting the situation in case of violation.

### Intellectual Property
In practice, it is very difficult to defend an idea. Instead, intellectual property laws are written to protect the material results of an idea. In other words, just inventing a song in your head is not protected, but if you record it, it can be protected.
Intellectual property protection is important because it gives people an incentive to be creative. Innovators with great ideas are more likely to follow these ideas if they have a clear idea of what benefits they will receive. In Article 8 of Section 8 of the U.S. Constitution, the authors found it appropriate to recognize the importance of protecting creative works:
Congress has the power. . . To promote the progress of science and useful arts, providing for a limited time to authors and inventors the exclusive right to their respective writings and discoveries.
If it is discovered that someone is using my image, I, as the copyright owner, can issue an invoice or even file a claim for damages. At this moment there is practically no room for negotiations. I have to be paid whatever I present. In this digital world, it's really very easy to search for offensive images using reverse search. This makes it easy to fall into the trap of using images incorrectly.

### Information Collection
HIPAA ensures the confidentiality and security of protected medical information.
FERPA acts to protect the confidentiality of student education records.
COPPA Children’s Online Privacy & Protection Act - governs the collection, use, and disclosure of personal information collected from children under age 13.


## Conclusion
In this unit, we studied various database models and practiced performing database queries using SQL (Structured Query language).
We got acquainted with the intellectual data protection and also studied the Ethical and legal consequences
