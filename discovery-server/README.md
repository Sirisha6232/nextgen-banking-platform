# discovery-server

Spring Boot Eureka Discovery Server for NextGen Banking Platform.

This module provides service registration and discovery for microservices.

Quick start (requires Maven & Java 21):

```powershell
cd "C:\Users\Sirisha Sankurathri\backend\nextgen-banking-platform\discovery-server"
mvn -U clean package -DskipTests
java -jar target\discovery-server-*.jar
```

Run with Docker:

```powershell
cd "C:\Users\Sirisha Sankurathri\backend\nextgen-banking-platform\discovery-server"
docker build -t nextgenbank/discovery-server:latest .
docker run -p 8761:8761 nextgenbank/discovery-server:latest
```

Notes:
- The existing `pom.xml` uses the parent project `nextgen-banking-platform`. Keep versions aligned when upgrading Spring Boot / Spring Cloud.

