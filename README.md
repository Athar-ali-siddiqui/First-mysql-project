# First-mysql-project

~categories
(1,'medicene')
(2,'cloth'),
(3,'frozen'),

~companies
(1,'knsLRG','large','E1836B'),
(2,'dawnSML','small','E1473B'),
(3,'mon salwaINT','international','E0997Y'),
(4,'levisINT','international','E0632Y'),
(5,'oxfordINT','international','E4364Y'),
(6,'shazaib hasanSML','small','E2347B'),
(7,'zainabSML','small',NULL),
(8,'ofiveLRG','large','E1347B'),
(9,'sanofiSML','small','E9847B'),
(10,'abbotINT','international','E2744Y'),
(11,'gskLRG','large','E2347B'),

~products
(name, wholesale, retail, qnty, cat_id,comp_id)

('Akns',10,15,237,3,1),
('Bkns',15,25,147,3,1),
('Adawn',8,15,207,3,2),
('Bdawn',13,24,197,3,2),
('Bmonsal',18,35,547,3,3),
('Cmonsal',30,50,47,3,3),
('Agsk',5,10,1000,1,11),
('Bgsk',3,7,1000,1,11),
('Cgsk',10,20,1000,1,11),
('Bsanofi',5,9,1000,1,9),
('Dsanofi',1,7,1000,1,9),
('Esanofi',15,20,1000,1,9),
('Aabbot',7,15,1000,1,10),
('Cabbot',15,30,1000,1,10),
('Eabbot',14,21,1000,1,10),
('Alevis',20,40,1000,2,4),
('Clevis',25,45,1000,2,4),
('Elevis',5,10,1000,2,4),
('Foxford',3,8,1000,2,5),
('Goxford',50,150,1000,2,5),
('Fsh',2,6,1000,2,6),
('Csh',20,35,1000,2,6),
('Ash',15,30,1000,2,6),
('Azainab',10,20,1000,2,7),
('Czainab',15,30,1000,2,7),
('Fzainab',1,4,1000,2,7),
('Gzainab',45,100,1000,2,7),
('Qofive',23,30,1000,2,8),
('Fofive',25,35,1000,2,8),

~customer
('A'),('B'),('C'),('D'),('E'),('F'),('G'),
('H'),('I'),('J'),('K'),('L'),('M'),('N'),
('O'),('P'),('Q'),('R'),('S'),('T'),('U'),
('V'),('W'),('X'),('Y'),('Z')

~purchased

insert into purchased (cust_id,p_id,quantity) values
(1 , 1, 4),
(1 , 9, 2),
(1 , 8, 4),
(1 ,7 , 6),
(1 , 6, 2),
(1 , 5, 4),
(2 , 5, 2),
(2 , 4, 1),
(2 , 3, 1),
(2 , 11, 1),
(3 , 15, 1),
(3 , 16, 4),
(4 , 17, 2),
(4 , 18, 3),
(4 , 19, 2),
(4 , 21,4 ),
(5 , 22, 2),
(6 , 19, 1),
(6 , 21, 4),
(6 , 23, 5),
(6 , 24, 2),
(7 , 13, 4),
(7 , 12, 2),
(7 , 7, 2),
(7 , 21, 3),
(8 , 17, 2),
(8 , 18, 1),
(8 , 6, 3),
(8 , 2, 5),
(8 ,4 , 4),
(9 , 6, 2),
(9 , 12, 1),
(9 , 18, 2),
(9 , 1, 3),
(9 , 11, 4),
(10, 4, 2),
(10, 12, 1),
(10, 6, 2),
(10, 8, 4),
(10, 9, 2),
(11, 19, 3),
(11, 15, 2),
(11, 1, 1),
(11, 2, 2),
(11, 3, 2),
(11, 7, 2),
(11, 6, 1),
(12, 3, 2),
(12, 24, 4),
(12, 29, 5),
(12, 17, 3),
(12, 13, 4),
(12, 19, 5),
(12, 11, 3),
(12, 20, 5),
(13, 27, 5),
(13, 10, 2),
(13, 7, 2),
(13, 8, 4),
(13, 6, 5),
(13, 9, 2),
(13, 11, 3),
(13, 21, 2),
(13, 12, 1),
(13, 13, 1),
(13, 14, 2),
(13, 15, 3),
(14, 17, 2),
(14, 16, 3),
(14, 18, 3),
(14, 22, 2),
(14, 1, 2),
(14, 2, 2),
(14, 3, 1),
(14, 21, 1),
(14, 4, 1),
(14, 5, 1),
(14, 6, 2),
(14, 7, 2),
(15, 8, 3),
(15, 28, 4),
(15, 29, 2),
(15, 27, 2),
(15, 26, 2),
(15, 25, 6),
(15, 24, 3),
(15, 5, 3),
(16, 27, 5),
(16, 29, 2),
(16, 28, 2),
(16, 1, 3),
(17, 2, 5),
(17, 3, 4),
(17, 4, 3),
(17, 5, 5),
(17, 10, 4),
(17, 7, 2),
(18, 8, 7),
(18, 6, 2),
(18, 9, 5),
(18, 11, 4),
(18, 21, 2),
(18, 12, 3),
(18, 13, 5),
(19, 14, 4),
(19, 15, 2),
(19, 17, 6),
(19,16 , 3),
(19, 18, 6),
(19, 22, 1),
(19,23 , 3),
(19, 24, 2),
(19, 26, 6),
(20, 16, 1),
(20,18 , 1),
(20, 19, 1),
(20, 21, 1),
(20, 5, 3),
(20, 3, 2),
(21, 11, 3),
(21, 13, 2),
(21, 12, 3),
(21, 14, 1),
(21, 15, 6),
(21, 9, 4),
(21, 10, 6),
(22, 1, 1),
(22, 2, 1),
(22, 3, 2),
(22, 13, 2),
(22, 4, 3),
(22, 5, 2),
(22, 6, 3),
(22, 7, 3),
(23, 8, 1),
(23, 28, 6),
(23, 29, 3),
(23, 27, 5),
(23, 26, 2),
(24, 25, 3),
(24, 24, 4),
(24, 1, 2),
(24, 23, 3),
(24, 22, 2),
(24, 21, 3),
(25, 11, 1),
(25, 4, 2),
(25, 12, 5),
(25, 6, 2),
(25, 8, 1),
(25, 9, 5),
(25, 19, 4),
(25, 15, 2),
(26, 1, 1),
(26, 2, 2),
(26, 3, 1),
(26, 7, 3),
(26, 6, 1),
(26, 10, 1),
(26, 24, 1),
(26, 29, 1),
(26, 17, 4),
(26, 13, 1),
(26, 19, 2),
(26, 11, 1),
(26, 20, 3),
(26, 27, 10);

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~QUERIES~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Q1 - How much products is left ?

Query:
select pro.p_id,(pro.quantity-pur.quantity) from products  pro INNER JOIN
(select p_id,sum(quantity) as quantity from purchased group by p_id) pur
ON (pur.p_id = pro.p_id);

Answer:
+------+-----------------------------+
| p_id | (pro.quantity-pur.quantity) |
+------+-----------------------------+
|    1 |                         220 |
|    2 |                         130 |
|    3 |                         192 |
|    4 |                         181 |
|    5 |                         527 |
|    6 |                          22 |
|    7 |                         978 |
|    8 |                         976 |
|    9 |                         980 |
|   10 |                         987 |
|   11 |                         980 |
|   12 |                         984 |
|   13 |                         981 |
|   14 |                         993 |
|   15 |                         984 |
|   16 |                         989 |
|   17 |                         981 |
|   18 |                         984 |
|   19 |                         982 |
|   20 |                         992 |
|   21 |                         980 |
|   22 |                         993 |
|   23 |                         989 |
|   24 |                         984 |
|   25 |                         991 |
|   26 |                         990 |
|   27 |                         973 |
|   28 |                         988 |
|   29 |                         987 |
+------+-----------------------------+
.............................................................................
Q2 - Most selling thing(category)?

Query: 
select c.cat_id,c.cat_name,products.p_name from products INNER JOIN
(select p_id,sum(quantity) from purchased group by p_id having sum(quantity) =(select distinct(sum(quantity)) as a from purchased group by p_id order by a desc limit 1)) p2 
ON p2.p_id = products.p_id
INNER JOIN categories c ON c.cat_id = products.cat_id;

Answer:
+--------+----------+---------+
| cat_id | cat_name | p_name  |
+--------+----------+---------+
|      2 | cloth    | Gzainab |
+--------+----------+---------+
.............................................................................
Q3 - Top 5 selling products ?

Query:
select pro.p_name, p1.p_id,p1.b as Quantity from (select p_id , sum(quantity) as b from purchased group by p_id) p1 
Inner join (select sum(quantity) as a from purchased group by p_id order by a desc limit 5) p2 On p1.b = p2.a 
INNER JOIN products pro On pro.p_id = p1.p_id;

Answer:
+---------+------+----------+
| p_name  | p_id | Quantity |
+---------+------+----------+
| Gzainab |   27 |       27 |
| Cmonsal |    6 |       25 |
| Bgsk    |    8 |       24 |
| Agsk    |    7 |       22 |
| Fsh     |   21 |       20 |
| Dsanofi |   11 |       20 |
| Cgsk    |    9 |       20 |
| Bmonsal |    5 |       20 |
+---------+------+----------+
.............................................................................
Q4 - Top 5 most profitable products ?

Query:

select p1.p_id,p1.p_name,p1.Profit from (select p_id , p_name , (retail_price - wholesale_price ) as Profit from products ) p1 
Inner join (select distinct(retail_price - wholesale_price ) as Profit from products order by Profit desc limit 5) p2 
On p1.Profit =p2.Profit order by p2.Profit desc;

Answer:
+------+---------+--------+
| p_id | p_name  | Profit |
+------+---------+--------+
|   20 | Goxford |    100 |
|   27 | Gzainab |     55 |
|   16 | Alevis  |     20 |
|    6 | Cmonsal |     20 |
|   17 | Clevis  |     20 |
|    5 | Bmonsal |     17 |
|   25 | Czainab |     15 |
|   22 | Csh     |     15 |
|   23 | Ash     |     15 |
|   14 | Cabbot  |     15 |
+------+---------+--------+
.............................................................................

Q5 - Customers net bill ?

Query:
select pur.cust_id,sum(pur.quantity*pro.retail_price) from purchased pur INNER JOIN products pro ON (pur.p_id=pro.p_id) group by pur.cust_id ;

Answer:
+---------+------------------------------------+
| cust_id | sum(pur.quantity*pro.retail_price) |
+---------+------------------------------------+
|       1 |                                428 |
|       2 |                                116 |
|       3 |                                181 |
|       4 |                                160 |
|       5 |                                 70 |
|       6 |                                222 |
|       7 |                                138 |
|       8 |                                471 |
|       9 |                                213 |
|      10 |                                236 |
|      11 |                                231 |
|      12 |                               1291 |
|      13 |                               1047 |
|      14 |                                590 |
|      15 |                                764 |
|      16 |                                675 |
|      17 |                                488 |
|      18 |                                424 |
|      19 |                                801 |
|      20 |                                199 |
|      21 |                                401 |
|      22 |                                422 |
|      23 |                                800 |
|      24 |                                378 |
|      25 |                                436 |
|      26 |                               1892 |
+---------+------------------------------------+
.............................................................................

