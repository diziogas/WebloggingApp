show databases;
use <name of database>;
create table <name of table> (username varchar(25) primary key not null,password varchar(25) not null);
show tables;
describe <name of table>;
select * from <name of table>;
insert into <name of table> (username,password) values("dsda","2134");


ston okeano
egkathistas mysql-server

theleis na antikatastiseiw to port apo 300kati se 8000.
ekteleis ayto ->  sudo cp mysqld.cnf /etc/mysql/mysql.conf.d/mysqld.cnf

gia na anastiseiw ti vasi dedomenwn
import a database->  sudo mysql -u diziogas -p Account < dump-Account.sql
export a database->  mysqldump -u diziogas -p Account > dump-Account.sql
