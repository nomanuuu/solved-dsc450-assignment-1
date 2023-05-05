Download Link: https://assignmentchef.com/product/solved-dsc450-assignment-1
<br>
<strong>Part 1</strong>

<ol>

 <li>Create a relational schema with underlined (primary) keys and arrows connecting foreign keys and primary keys for a database containing the following information. If you have any difficulty drawing arrows, you can write foreign key information in a sentence instead.</li>

</ol>




<ul>

 <li><strong>Authors</strong> have Last Name, Firstname, ID, and Birthdate (identified by ID)</li>

 <li><strong>Publishers</strong> have Name, ID, address (identified by ID)</li>

 <li><strong>Books</strong> have ISBN, Title, Publisher (each book has a unique publisher and can be identified by ISBN).</li>

 <li>Authors <strong>Write</strong> Books; since many authors can co-author a book, we need to know the rank of an author contributing to a book, stored in this table (i.e. a number 1, 2, 3; for single author books, this number is 1).</li>

</ul>

NOTE: Part 2 has some sample data which may be helpful.










<ol>

 <li>Create a relational schema for students and student advisors</li>

</ol>

<ul>

 <li><strong>Students</strong> have First Name, Last Name, DOB, Telephone and a reference to their advisor</li>

 <li><strong>Advisors </strong>have ID, Name, Address, Research Area</li>

</ul>




<strong>Part 2</strong>




<ul>

 <li>Using your logical schema from Part1-a, write the necessary SQL DDL script to create the tables. Be sure to specify every primary key and every foreign key. You can make <u>reasonable</u> assumptions regarding the attribute domains (note that uniformly setting every column to <em>VARCHAR2(100)</em> is <u>not reasonable</u>).</li>

</ul>




<ul>

 <li>Using logical schema from Part1-b write the necessary SQL DDL script to create the tables. Be sure to specify every primary key and every foreign key. For <strong>Students</strong> table, clearly state the assumptions you have made when choosing a primary key. You can make reasonable assumptions regarding the attribute domains.</li>

</ul>













<ul>

 <li>Write SQL INSERT statements to populate your database from Part1-a with the following data (NOTE: remember that strings would need to use single quotes, e.g., ‘Asimov’)</li>

</ul>








































<strong>Part 3</strong>

You want to create a relation representing US presidents. Suppose that the following is true of the data you want to represent:




<ul>

 <li>No two presidents have the same name and year of birth</li>

 <li>No two presidents have the same inauguration date</li>

 <li>All presidents have a name, a year of birth, and have been inaugurated into office</li>

 <li>Not all presidents are affiliated with a political party</li>

</ul>




Write a valid create table statement for the relation.




<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>Part 4</strong>




Let R(ABCDEFGH) satisfy the following functional dependencies:

A → B, CH → A, B → E, BD → C, EG → H, DE → F.

Use transitive rule to find additional F.D.s that are satisfied by R?

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>Part 5</strong>




Consider a MEETING table that records information about meetings between clients and executives in the company.  Each record contains the names of the client and the executive’s name as well as the office number, floor and the building.  Finally, each record contains the city that the building is in and the date of the meeting.  The table is in First Normal Form and the primary key is (Client, Office).

(Date, <u>Client</u>, <u>Office</u>, Floor, Building, City, Executive)

<strong> </strong>

You are given the following functional dependencies:

Building → City

Office → Floor, Building, City

Client → Executive

Client, Office → Date




<ol>

 <li>Remove any existing partial dependencies and convert the logical schema to the Second Normal Form.  Please remember that when performing schema decomposition, you need to denote primary key for every new table as well as the foreign key that will allow us to reconstruct the original data.</li>

</ol>













<ol>

 <li>Remove any existing transitive dependencies to create a set of logical schemas in Third Normal Form.  Again, remember to denote primary keys and foreign keys (including which primary key those foreign keys point to).</li>

</ol>










<strong>Part 6</strong>




Consider a table that stores information about students, student name, GPA, honors list and the credits that the student had completed so far.




(<u>First</u>, <u>Last</u>, GPA, Honor, Credits)




You are given the following functional dependencies




First, Last → GPA, Honor, Credits

GPA → Honor




<ol>

 <li>Is this schema in Second Normal Form?  If not, please state which FDs violate 2NF and decompose the schema accordingly.</li>

</ol>













<ol>

 <li>Is this schema in Third Normal Form?  If not, please state which FDs violate 3NF and decompose the schema accordingly.</li>

</ol>

<strong> </strong>


