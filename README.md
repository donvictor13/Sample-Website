# Sample Website For Testing 

Here is a sample PHP website that can be made use of for testing purposes. 

## For Testing the Database Connectivity

```sh

# vim index.php

<?php
  
// Database Connection

$user = 'Provide-Your-Username';         
$password = 'Provide-Your-Username'; 
$database = 'Provide-Your-Database-Name'; 
$servername='Provide-Host-Details';
```

## Sample Database Creation Steps

```sh

########################################################################
Example Database
########################################################################

create database college;
use college;

########################################################################
Example table
########################################################################

CREATE TABLE students(
name VARCHAR(20) NOT NULL,
age INT(3) NOT NULL,
email VARCHAR(30) NOT NULL
);

########################################################################
Example table content
########################################################################
INSERT INTO students(name,age,email) VALUES('kevin',20,'kevin@gmail.com');
INSERT INTO students(name,age,email) VALUES('sam',24,'sam@gmail.com');
INSERT INTO students(name,age,email) VALUES('john',23,'john@gmail.com');
INSERT INTO students(name,age,email) VALUES('jane',25,'jane@gmail.com');
INSERT INTO students(name,age,email) VALUES('devon',23,'devon@gmail.com');
INSERT INTO students(name,age,email) VALUES('nelson',22,'nelson@gmail.com');
```
