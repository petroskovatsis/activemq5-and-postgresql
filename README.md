# activemq5-and-postgresql

Custom Docker image for ActiveMQ with PostgreSQL database.

#### Download the ActiveMQ

* Command line
```
./download-activemq.sh
```

#### Build and run the Docker image

* Build and tag the image
```
docker build -t pk/activemq .
```

* Run
```
docker run --rm -d -p 8161:8161 pk/activemq 
```

* Check your localhost at port `8161`

```
http://localhost:8161
```