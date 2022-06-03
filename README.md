# JPA
전자정부 프레임워크 4.0 버전으로 연결하는
jpa 세팅법 

사용한 pom.xml에서 추가한 라이브러리들 
<dependency> <!-- JPA 사용을 위한 Dependency -->
    	<groupId>org.hibernate</groupId>
    	<artifactId>hibernate-entitymanager</artifactId>
    	<version>5.0.12.Final</version>
    	<type>pom</type>
	</dependency>
	
	<dependency>
    	<groupId>com.querydsl</groupId>
    	<artifactId>querydsl-jpa</artifactId>
    	<version>4.1.4</version>
	</dependency>
 	
	<dependency>
    	<groupId>com.querydsl</groupId>
    	<artifactId>querydsl-apt</artifactId>
    	<version>4.1.4</version>
    	<scope>provided</scope>
	</dependency>
	
	<dependency>
    	<groupId>org.apache.poi</groupId>
    	<artifactId>poi</artifactId>
    	<version>4.1.2</version>
	</dependency>
	<dependency>
   	 	<groupId>org.apache.poi</groupId>
   		<artifactId>poi-ooxml</artifactId>
    	<version>4.1.2</version>
	</dependency>
