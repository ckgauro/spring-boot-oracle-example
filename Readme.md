# Spring Boot Oracle Example

* To run this example you will need to download and install the Oracle JDBC driver.
* You can install the Oracle Jar into your local Maven repsository using this command: `mvn install:install-file -Dfile=ojdbc7.jar -DgroupId=com.oracle -DartifactId=ojdbc7 -Dversion=12.1.0.2 -Dpackaging=jar`



## to Run Oracle container in docker
docker run -p 27017:27017 -v /Users/ckgauro/dockerdata/oracle  -d mongo
docker run --name=OracleXe -d -p 1521:1521 -v /Users/ckgauro/dockerdata/oracle oracleinanutshell/oracle-xe-11g

## to restart container
docker restart ```<container ID>```

## to Browse
http://localhost:8080/product/list

