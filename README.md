# MySQL-LAB-SHEET-01

1. Use your database and
a. Write a SQL statement to create a simple table called ‘countries’ including the fields, country_id, country_name and region_id. (Use suitable data types)
b. Write a SQL statement to insert a record with your own values into the table countries against each field.

2. In your database
2.1 Create a simple table called ‘student_details’ with the fields, student_id, student_name, date_of_birth, phone_number, gender (‘M’, ‘F’) and food_preference (‘vegi’, ‘fish’, ‘egg’, ‘chicken’).
* Use suitable data types for the fields.
* student_id and student_name fields should not be null.
* Phone_number should have the format XXX-XXXXXXX.
* Set the default food_preference to be ‘vegi’.

2.2 Insert the following set of data into the table.

|student_id | student_name | date_of_birth | phone_number | gender | food_preferance|
|-----------|----------|----------|----------|----------|----------|---------------|
1 | Kasun Perera | 1993-12-02 | 081-2234515 | M | chicken
2 | Nimali Jayasinghe | 1994-03-11 | 011-2145892 | F | vegi
3 | Fathima Nuzra | 1993-11-08 | 081-2323114 | F | vegi
4 | Nimal Fernando | 1993-04-05 | 011-5645789 | M | fish
5 | Charuni Perera | 1995-09-12 | 036-1123452 | F | egg

2.3 Write the SQL statement to display all the details in your table.
2.4 Write the SQL statement to display details of ‘Charuni Perera’.
2.5 Write the SQL statement to display all the male students.
2.6 Write the SQL statement to display all the female students who prefer ‘vegi’.
2.7 Write the SQL statement to display all the students born between 1993-01-31 to 1993-12-31.
2.8 Write the SQL statement to display students whose name starts with ‘N’.

3. In your database create a table with the following structure. You may use an appropriate table name.

|Field | Type | Null | Key | Default | Extra|
|-----------|----------|----------|----------|----------|----------|
Emp_id | INT | NO | | | 
Emp_name | VARCHAR(30) | NO | | | 
Salary | FLOAT(7,2) | YES | | 10000.00 | 
Department | ENUM(‘HR’, ‘ADMIN’, ‘COM’) | YES | | ADMI | 
