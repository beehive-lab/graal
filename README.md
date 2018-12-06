 
Branch for holding the maven packages that correspond to the Graal version that is used in Tornado


## How to use it?

Insert this in your pom file:

```!xml
   <repositories>
     <repository>
       <id>universityOfManchester-graal</id>
       <url>https://raw.githubusercontent.com/beehive-lab/graal/maven-tornado-repos</url>
     </repository>
   </repositories>
  
   <dependencies>   
      <dependency>
         <groupId>graal</groupId>
         <artifactId>graal</artifactId>
         <version>0.22</version>
      </dependency>
       <dependency>
         <groupId>graal</groupId>
         <artifactId>truffle-api</artifactId>
         <version>0.22</version>
       </dependency>
   </dependencies>
```

