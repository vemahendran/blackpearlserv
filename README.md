# blackpearlserv
A sample spring boot application

#### Commands
```
mvn clean install -Dmaven.test.skip=true
java -jar target/blackpearlserv-1.0.0.jar
```

Docker commands:
```
docker build -t vemahendran:blackpearlserv .
docker run --name demo-spring -p 9090:9090 vemahendran/blackpearlserv
```

To delete the container name:
```
docker rm -f <container_id>
```
