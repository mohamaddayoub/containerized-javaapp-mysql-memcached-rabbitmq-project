## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later
######
## Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
## Database
Here,we used Mysql DB

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql
## Validation
> the login page of the web application:

> Validate the database connection:

> Validate the Memcache connection:

> Validate data is coming from Database when user first time requests it:

> Validate data is coming from Memcached when user second time requests it:
> 













