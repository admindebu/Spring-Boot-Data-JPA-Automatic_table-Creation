# Spring-Boot-Data-JPA-Automatic_table-Creation
This example show you how to create table with spring Data Jpa with out Flyway while your application will up and running

# Need to add Spring Data JPA dependency in POM
<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-data-jpa</artifactId>
		</dependency>
# Use @Entity ( at the top of the class ) and @Id ( on primary key ) annotation in the model / domain class
#  Add below configuration in application file 
spring.jpa.hibernate.ddl-auto=create  ( only for create )
or
spring.jpa.hibernate.ddl-auto = update ( create and update - this is more preferable )

That's all... RUn your Application 

# My YouTube Video LInk for this Solution : https://youtu.be/8frWD5z1m78
# Follow me on FackBok Page : techtalk debu
