FROM openjdk:8-jre-alpine

EXPOSE 8080

# Copy war file
ADD docker/devops-accelerator.war devops.accelerator.war
# COPY devops-accelerator.war /devops-accelerator.war

# run the app
ENTRYPOINT ["/usr/bin/java", "-jar", "devops-accelerator.war"]


