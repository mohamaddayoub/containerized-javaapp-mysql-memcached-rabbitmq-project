![mult-tier Web App](https://github.com/mohamaddayoub/containerized-javaapp-mysql-memcached-rabbitmq-project/assets/49444800/f3221c3b-3e3c-462b-ae9c-ef63232987ca)
## Multi-tier Web Application:
> MySQL (Database SVC).
> Memcache (DB Caching SVC).
> RabbitMQ (Broker/Queue SVC).
> Tomcat (Application SVC).
> Nginx (Web SVC).
###
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

![Validate1](https://github.com/mohamaddayoub/containerized-javaapp-mysql-memcached-rabbitmq-project/assets/49444800/2a0f216a-3b16-467a-b5ad-0be2dced2dc0)
> Validate the database connection:

![Validate2](https://github.com/mohamaddayoub/containerized-javaapp-mysql-memcached-rabbitmq-project/assets/49444800/f85e3b20-5490-4b16-8528-e5a6a1222a97)
> Validate the Memcache connection:

![Validate3](https://github.com/mohamaddayoub/containerized-javaapp-mysql-memcached-rabbitmq-project/assets/49444800/e1f6425f-6111-4b83-bf64-efc6d5e4130b)
> Validate data is coming from Database when user first time requests it:

![Validate4](https://github.com/mohamaddayoub/containerized-javaapp-mysql-memcached-rabbitmq-project/assets/49444800/d5a9741d-a235-4b9d-bbd5-2c5aff8a5910)
> Validate data is coming from Memcached when user second time requests it:

![Validate5](https://github.com/mohamaddayoub/containerized-javaapp-mysql-memcached-rabbitmq-project/assets/49444800/e7211592-c686-42ce-8016-1736692b8cb8)













