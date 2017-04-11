# Docker Cassandra Web
This project in only the  [cassandra web](https://www.google.com) application containerized!

**Command:**  
   docker run -d --name cassandra-web \  
  -e CASSANDRA_HOST_IP=127.0.0.1 \   
  -e CASSANDRA_PORT=9042 \  
  -e CASSANDRA_USERNAME=user \  
  -e CASSANDRA_PASSOWRD=pass \  
  -p 3000:3000 \  
  delermando/docker-cassandra-web:v0.4.0
 
