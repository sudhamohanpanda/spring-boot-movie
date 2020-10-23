#version 1:
##Features:
Use JDK 11, spring-boot 2.3.3
##Steps:
- git clone from https://spring.io/guides/gs/spring-boot/
    - git clone https://github.com/spring-guides/gs-spring-boot.git
- Delete gradle related files, initial folder and move the contain of complete folder to root folder
- In pom change to:
```
 <groupId>com.smp</groupId>
 <artifactId>spring-boot-movie</artifactId>
 <version>0.0.1-SNAPSHOT</version>
 <name>spring-boot-movie</name>
 <description>Demo project for Spring Boot</description>

 <properties>
 	<java.version>11</java.version>
 </properties>
```
Rename root folder to spring-boot-movie
Import project in Intellij as File => new => Project from existing source
- `mvn clean install`

- In github create new repository
```
git remote add origin https://github.com/sudhamohanpanda/spring-boot-movie.git
git branch -M main
git push -u origin main
```
Done - is not it simple
