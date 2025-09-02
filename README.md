/*Insert new user data 
● Update existing records 
● Delete specific rows 
● Write SELECT queries with conditions, sorting, and limits*/

select * from users;

//Insert new user data 
insert into users (username,firstName,lastname,age) values ("Priya_M","Priya","Meher",38);

● Update existing records 
UPDATE USERS SET firstname = "Priyanka" where lastname = "Meher";

● Delete specific rows 
DELETE FROM USERS WHERE firstname = "Priyanka" ;

● Write SELECT queries with conditions, sorting, and limits*/
select * from users where username = "slee";
select * from users where id < 7 order by firstname ASC;
select * from users limit 10 offset 7;
