# HomeWork8


create table employee (
	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);



update employee
set name = 'faaaaa',
	birthday = '2022-02-26' ,
	email = 'arda.ard@gmail.com'
	
where name like '%a'
returning *;


delete from employee
where id>6 and id<11
returning *;
