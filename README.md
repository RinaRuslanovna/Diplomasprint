# Diplomasprint
scooter_rent=# select c.login, count(*) from "Couriers" c join "Orders" o on o."courierId"=c.id where o."inDelivery"='t' group by c.login;

 
 
 login | count
-------+-------
 nina  |     4
(1 row)


