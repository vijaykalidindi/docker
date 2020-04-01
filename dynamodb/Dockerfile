FROM amazon/dynamodb-local:latest
CMD [ "-jar", "DynamoDBLocal.jar", "-sharedDb" ]
 
# For Spring-Boot project, use the entrypoint below to reduce Tomcat startup time.
#ENTRYPOINT exec java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar docker.jar
