# Write your MySQL query statement below
select u.name as Name, sum(t.amount) as Balance from users u left join transactions t on u.account=t.account group by u.name having sum(t.amount)>10000;