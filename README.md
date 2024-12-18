#sql querys
```SQL
select * from students where YEAR(date_of_birth) =1990;

select * from courses where cfu > 10;

select * from students where YEAR(CURDATE()) - YEAR(date_of_birth) > 30;

select * from courses where period ='I semestre' and year=1;

select * from exams where date = '20-06-20' and hour > '14:00:00';



```