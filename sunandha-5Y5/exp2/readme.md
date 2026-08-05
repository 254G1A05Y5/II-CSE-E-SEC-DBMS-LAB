#CREATE STUDENT TABLE
```
CREATE TABLE student(
name VARCHAR2(30),
student_number NUMBER,
class NUMBER,
major VARCHAR2(20)
);
```
# DESCRIBE STUDENT TABLE
```
DESC STUDENT;
```
##INSERT STUDENT TABLE
```
INSERT INTO student
VALUES('smith',17,1,'cs');
INSERT INTO student
VALUES ('brown',8,2,'cs');
```
## DISPLAY STUDENT TABLE
```
SELECT * FROM student;
```
