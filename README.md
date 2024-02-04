Create basic maven project using CMD (powershell may throw up errors):
mvn archetype:generate -DgroupId=com.example -DartifactId=<PROJECT NAME HERE> -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
Remove the generated src directory, this is not required
Generate two new modules one for the angular application and one for the spring application
![image](https://github.com/Tenbetter/angular-spring-demo/assets/60200535/1c266068-aa92-4c56-aa1e-612f5efa8d8a)



delete the generated src directories in the new modules.

project structure and parent pom should look like this


Generate a spring application via [](https://start.spring.io/)https://start.spring.io/
Download and extract to the spring api module

