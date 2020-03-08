# mysql-docker-container

### Start mysql command
`$ start-mysql.sh`

### Stop mysql command (will result in removing data)
`$ stop-mysql.sh`

### UI access
URL: `http://localhost:8080`

User: `root`

Password: `example`

### Spring `application.properties` settings
```
# DATASOURCE (DataSourceAutoConfiguration & DataSourceProperties)
spring.datasource.url=jdbc:mysql://localhost:3306/polling_app?useSSL=false&serverTimezone=UTC&useLegacyDatetimeCode=false&allowPublicKeyRetrieval=true

spring.datasource.username=test1
spring.datasource.password=example

## Hibernate Properties
# The SQL dialect makes Hibernate generate better SQL for the chosen database
# spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL5InnoDBDialect
# spring.jpa.hibernate.ddl-auto = update
```
