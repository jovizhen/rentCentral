# Pull base image
FROM java:8

# Maintainer
MAINTAINER "jovi <jovizhen@gmail.com">

# Copy to images tomcat path
ADD target/zuul-server.jar /

ENTRYPOINT ["java", "-jar", "/zuul-server.jar"]