# Hello rest spring boot

### TEST
```
figlet clean
./gradlew clean

figlet test
./gradlew test
```

### Build
```
figlet jar
./gradlew bootJar
```

### RUN
```
figlet cp
cp build/libs/rest-service-0.0.1-SNAPSHOT.jar ~/app/hello-rest-sb

figlet java jar
java -jar /home/jsmin630/app/hello-rest-sb/rest-service-0.0.1-SNAPSHOT.jar

curl http://localhost:8080/hello
```


___
## version
### 0.1.0 hello
