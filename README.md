# SQL Ödev 2
select * from Products 
where UnitsInStock  BETWEEN  17 and 29;

select * from Customers
where CompanyName  IN ('Ana%', 'Bo%','C%') ;

select UnitsOnOrder,ReorderLevel from Products 
where UnitsOnOrder IN (0,10,60) and ReorderLevel  IN (25, 0,30);
