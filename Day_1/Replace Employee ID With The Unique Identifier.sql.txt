# Write your MySQL query statement below
select e.name,em.unique_id from employees e left join employeeUNI em on e.id=em.id; 