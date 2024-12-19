#group by

```SQL
 select year(enrolment_date) as enrolment_year (*) from students group by enrolment_year order by enrolment_year desc;

 select CAST(office_number AS UNSIGNED) AS office_number_numeric, count(*) as teachers_number from teachers group by office_number_numeric order by office_number_numeric asc;

 select exam_id, count(*) as student_count, avg(vote) as avg from exam_student group by exam_id;

 select department_id,count(*) as deegres_number from degrees group by department_id;

 



```