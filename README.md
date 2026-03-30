# dbms_lab6

how to run SQL file 
1) open pgAdmin
2) make sure the tables are loaded (Student, Courses and Enrollments)
3) open the cmpt308_lab6.sql file
4) run the file. read the comments

summary
before indexing: SQL used Seq Scan on Enrollments, where it checked every row. 
after indexing: SQL used an Index Scan for filtering the quieres, which is a useful tool. 
join query results: the join query stayed the same.
