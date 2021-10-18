# Running the application
- Please enter the correct credentials in twitter4j.properties file in twitter-to-kafka-service 
and enter your github password and url on bootstrap.yml file of config-server
- Then run mvn install -DskipTests command
- Then run docker-compose up command in docker-compose folder
- Then run kafka-to-elastic-service in intelliJ
- Check new kafka-to-elastic-service, which is the 2nd microservice in our system