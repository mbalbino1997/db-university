#JOIN
 
```SQL
select * from students as s inner join degrees as d on s.degree_id=d.id where d.name like ("%economia%");

select * from degrees as d inner join departments as de on d.department_id = de.id where de.name = "Dipartimento di Neuroscienze" and d.level="magistrale";

select * from courses as c inner join course_teacher as ct on c.id = ct.course_id inner join teachers as t on ct.teacher_id=t.id where t.name = "fulvio" and t.surname = "amato";


```