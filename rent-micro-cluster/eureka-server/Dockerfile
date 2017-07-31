# Pull base image
FROM java:8

# Maintainer
MAINTAINER "jovi <jovizhen@gmail.com">

# Copy to images tomcat path
ADD target/eureka-server.jar /

ENTRYPOINT ["java", "-jar", "/eureka-server.jar"]