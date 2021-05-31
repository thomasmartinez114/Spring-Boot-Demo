**Spring Boot**

- Scope of Project
	- API Layer
		- GET, POST, PUT, DELETE
	- Service Layer
	- Data Access Layer
	- Database

- Spring Boot Dependencies
	- Spring Web
	- Spring Data JPA
	- PostgreSQL Driver

- Database
	- Install PostgreSQL
		- https://www.enterprisedb.com/downloads/postgres-postgresql-downloads
	- Add the following to resources/application.properties
		- spring.datasource.url=jdbc:postgresql://localhost:5432/student
		- spring.datasource.username=
		- spring.datasource.password=
		- spring.jpa.hibernate.ddl-auto=create-drop
		- spring.jpa.show-sql=true
		- spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect
		- sping.jpa.properties.hibernate.format_sql=true
