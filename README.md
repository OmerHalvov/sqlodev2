# sqlodev2
Patika Sql Ödev-2

Cevap-1:
select * from film where replacement_cost between 12.99 and 16.99;

Cevap-2:
SELECT first_name,last_name FROM actor WHERE first_name IN('Penelope','Nick','Ed');

Cevap-3:
select * from film where rental_rate in (0.99, 2.99, 4.99) and replacement_cost in (12.99, 15.99, 28.99)
