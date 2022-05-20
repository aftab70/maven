This is the Jave sample project to test your Apache tomcat server along with maven build tool.
=============================
## Requirment to perform this CI and CD 

- Git
- Java
- Maven
- VirtualBox
- Tomcat8 

## CI and CD Process

1. git clone https://github.com/aftab70/maven.git
2. cd maven
3. mvn package
4. cd target/
5. cp hello-v1.war <To your tomcat server inside webapps directory>
6. Done!!!!

## Open your browser at http://localhost:8080/hello-v1/ or http://YOUR_PUBLIC_IP:8080/hello-v1/ 
