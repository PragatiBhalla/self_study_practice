FROM tomcat:8
MAINTAINER PRAGATI BHALLA

# setup
COPY helloworld-1.1.war /usr/local/tomact/webapps/
RUN java -version


# Expose the ports we're interested in
EXPOSE 8080

# Set the default command to run on boot
CMD ["catalina.sh", "run"]
