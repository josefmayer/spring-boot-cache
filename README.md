## Spring Boot Cache
Spring Boot example with Spring cache abstraction <br />
Choose different chache implementations <br />


### Technologies
Caches, Spring Boot  <br />

### Supported Cache Implementations <br />
HazelCast <br />
EhCache <br />
Infinispan <br />
CouchBase <br />
Redis <br />
Simple provider based on ConcurrentHashMap <br />

### Data Structure
List \<String> <br />



### Steps
##### Build and run application
With spring-boot-maven plugin: <br /> 
*mvn clean compile* <br />
*mvn spring-boot:run -P\<cacheproviderprofile>* <br />

With spring-boot-maven plugin: <br /> 
Select cacheprovider by activating maven profile <br />  
*mvn clean compile* <br />
*mvn spring-boot:run* <br />


##### Build jar, run jar
Select cacheprovider by activating maven profile <br />  
*mvn clean compile package*  <br />
*java -jar target/jar_name.jar*

##### Setting maven profile active
    <activation>
        <activeByDefault>true</activeByDefault>
    </activation>




### Info
https://github.com/spring-projects/spring-boot/tree/master/spring-boot-samples/spring-boot-sample-cache

