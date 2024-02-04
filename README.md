Create basic maven project using CMD (powershell may throw up errors):
mvn archetype:generate -DgroupId=com.example -DartifactId=<PROJECT NAME HERE> -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
Remove the generated src directory, this is not required
Generate two new modules one for the angular application and one for the spring application
![image](https://github.com/Tenbetter/angular-spring/assets/60200535/2d3cd11b-07aa-4024-8183-980c6f2a03fa)
![image](https://github.com/Tenbetter/angular-spring/assets/60200535/e2fca23d-6b05-4f0e-ab31-f9643c45e068)

delete the generated src directories in the new modules.

project structure and parent pom should look like this
![image](https://github.com/Tenbetter/angular-spring/assets/60200535/d48be133-f270-4102-b9c0-7dd4a10dea07)

Generate a spring application via [](https://start.spring.io/)https://start.spring.io/
Download and extract to the spring api module
![image](https://github.com/Tenbetter/angular-spring/assets/60200535/976d2799-33da-40f2-8213-77f5ff39fbbc)
