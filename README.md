# todo_list_corephp
A todo list app with CRUD functionality with core PHP - No framework just pure php and mysql

## To Bootstrap

### Create a mysql database 
$ mysql -u root create database todoDb;

### Create to do table in the created db "todoDb"
$ mysql -u root todoDb;
create table todos(id int auto_increment primary key not null, name text);
exit
