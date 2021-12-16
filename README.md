## mysql commands refernce

create table student(id int(10) primary key, name varchar(100));


insert into student values(3,'guntupalli');


GRANT PRIVILEGE ON database.student TO 'admin'@'localhost';


GRANT ALL PRIVILEGES ON *.* TO 'admin'@'localhost' WITH GRANT OPTION;



curl localhost:9000/app/students
