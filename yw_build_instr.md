The app uses Java 8 and Maven. 
* service code are in the `./src` folder 
* disabled the `git-commit-id-plugin` plugin used by some services to avoid related failures

My build enironment: 
```
>  mvn --version
Apache Maven 3.8.2 (ea98e05a04480131370aa0c110b8c54cf726c06f)
Maven home: C:\Program Files\apache-maven-3.8.2
Java version: 1.8.0_302, vendor: Temurin, runtime: C:\Program Files\Eclipse Foundation\jdk-8.0.302.8-hotspot\jre
Default locale: en_CA, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"
```

To generate service jars: 
```
cd src
mvn clean package -DskipTests
```
