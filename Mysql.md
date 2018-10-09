# Mysql



### 2）.常用指令

​	1.将数据库打包成.sql文件

		> ​	mysqldump -u root -p database-name > filename.sql



​	2.执行.sql文件

​		方法一：在mysql的bin文件目录下

> mysql -u root -p -Ddatabase-name < .sql



​		方法二：source .sql