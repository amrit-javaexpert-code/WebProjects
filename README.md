To execute this project we need to :
1. Install java21 and Eclipse and Apache Tomcat 9.0 in your pc
2. Set up all the environmemts to work in Java .
3. Now We need to create Maven Project or we can directly import this into our Eclipse.
4. Make sure your Apache Tomcat Web Server should also be in running mode.
5. Also make sure to add all the necessary dependencies in your pom.xml file.
6. Following dependencies must be added into pom.xml file.
  <!-- https://mvnrepository.com/artifact/org.springframework/spring-webmvc -->
<dependency>
    <groupId>org.springframework</groupId>
    <artifactId>spring-webmvc</artifactId>
    <version>5.3.1</version>
</dependency>
    <!-- https://mvnrepository.com/artifact/javax.servlet/jstl -->
<dependency>
    <groupId>javax.servlet</groupId>
    <artifactId>jstl</artifactId>
    <version>1.2</version>
</dependency>

<!-- https://mvnrepository.com/artifact/org.hibernate/hibernate-core -->
<dependency>
    <groupId>org.hibernate</groupId>
    <artifactId>hibernate-core</artifactId>
    <version>5.4.23.Final</version>
</dependency>
<!-- https://mvnrepository.com/artifact/mysql/mysql-connector-java -->
<dependency>
    <groupId>mysql</groupId>
    <artifactId>mysql-connector-java</artifactId>
    <version>5.1.36</version>
</dependency>

<!-- https://mvnrepository.com/artifact/org.springframework/spring-orm -->
<dependency>
    <groupId>org.springframework</groupId>
    <artifactId>spring-orm</artifactId>
    <version>5.3.38</version>
</dependency>
7. But its better you must directly import the whole project, rather than making separate efforts.
8. After embedding this project, you can right click on Main Project "Project_CodeWithAmrit.com" and click on run on Server 
