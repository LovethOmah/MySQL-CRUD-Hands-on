Start Mysql on my local machine using: Sudo mysql
List the databases i have using: Show databases
->;

create a new dabase using: create a new database `< name of database>`
To use the database i created: use ` < name of database> `;
To create a new table in the database: create table if not exists ` name of table `(

create the profile you want as a primary key (strong): 
id int (data type) auto_increment primary key,
name varchar(60) (variable character) not null,
email varchar(45) not null,
age varchar(34) not null,
qualification varchar(5) not null,
hobbies varchar(10) not null,
created_at (time) timestamp default current_timestamp
);

To insert values into the columns: 
insert into ` name of table ` (name, email, age, qualification,hobbies) values (fill in the corresponding datas)
To see everything on my table:
select * from ` name of table `

To add more columns use "ALTER". This modifies the structure of the table
alter table `name of table`
-> add column <name of new column> varchar(6);

To add change or modify the values or records stored in the table column use "UPDATE"
update `name of table`
-> set <name of column> = value
-> where id (row id) = e.g 1;

To delete a database or table use "DROP"
drop database `<name of database>`;

To exit mysql, type exit
