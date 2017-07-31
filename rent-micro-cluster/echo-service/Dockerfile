# Pull base image
FROM java:8

# Maintainer
MAINTAINER "jovi <jovizhen@gmail.com">

# Copy to images tomcat path
ADD target/echo-service.jar /

ENTRYPOINT ["java", "-jar", "/echo-service.jar", "-Xdebug -Xrunjdwp:server=y,transport=dt_socket,suspend=n"]
