FROM java:8
MAINTAINER PRAGATI BHALLA

# setup
COPY helloworld-1.1.jar /opt/
RUN java -version


# Expose the ports we're interested in
EXPOSE 8080 9990 9090

# Set the default command to run on boot
CMD java -jar helloworld-1.1.jar
