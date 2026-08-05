## creating a course table
```
CREATE TABLE course(
course_name VARCHAR2(50),
course_number NUMBER,
credit_hours NUMBER,
department VARCHAR2(20)
);
```
##describing the table
```
DESC course;
```
## inserting a values
```
INSERT INTO course
VALUES('intro to computer science ',1301,4,'cs');
INSERT INTO course
VALUES('data structures',1321,4,'cs');
INSERT INTO course
VALUES('discrete mathematics',2302,3,'MATH');
INSERT INTO course
VALUES('data base',3380,3,'cs');
```
## display the course table
```
SELECT * FROM course;
```

