# Docker Cassandra Web
This project in only the  [cassandra web](https://www.google.com) application containerized!

**Command:**  
   docker run -d --name cassandra-web \  
  -e CASSANDRA_HOST_IP=192.168.200.3 \   
  -e CASSANDRA_PORT=9042 \  
  -e CASSANDRA_USERNAME=cassandra \  
  -e CASSANDRA_PASSOWRD=cassandra \ 
  -p 3000:3000 \  
  cassandra-web 
 
