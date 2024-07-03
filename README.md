# Springboot-setup
This is how to setup a springboot project on windows with powershell.

1. Use https://start.spring.io/ to install a springboot project with maven, java, and a stable version of springboot.
2. Change the group name and artifact name as you wish.
3. Click "generate" and extract the files somewhere.
4. Install maven from https://maven.apache.org/download.cgi, put the folder under the "C" directory, and add the "bin" folder to path for all users, and restart your terminal.
5. Find the java file which is at src\main\java\com\{group name}\{artifact name}\ and edit it to add some print statement to the main function.
6. Build with `mvn clean install` then run with `mvn spring-boot:run`.
7. You should see the printed text output to the console.

The source files were generated with Java 16, Spring 3.3.1, and Maven 3.9.8. The version of Java installed was 20.0.2.
