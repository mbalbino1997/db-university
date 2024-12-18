#sql querys
```SQL
select * from students where YEAR(date_of_birth) =1990;

select * from courses where cfu > 10;

select * from students where YEAR(CURDATE()) - YEAR(date_of_birth) > 30;

select * from courses where period ='I semestre' and year=1;

select * from exams where date = '20-06-20' and hour > '14:00:00';

select * from degrees where level='magistrale';

select count(*) from departments;

select count(*) from teachers where phone is null;

insert into students (degree_id,name, surname, date_of_birth, fiscal_code, enrolment_date, registration_number, email)
values
(60,'massimo','balbino','1997-07-17','BLBRCG97L17A662L', '2024-12-18','684123','rmassimo.balbino@gmail.com');

update teachers
set office_number=126
where name='pietro' and surname ='rizzo';



```