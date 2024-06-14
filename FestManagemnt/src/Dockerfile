# Use an official Tomcat image as a parent image
FROM tomcat:9.0.54-jdk11

# Set environment variables if needed
# ENV ...

# Copy the FestManagement WAR file from src directory to the webapps directory of Tomcat
COPY src/FestManagemnt.war /usr/local/tomcat/webapps/

# Expose the port on which Tomcat runs (default is 8080)
EXPOSE 8080

# Start Tomcat
CMD ["catalina.sh", "run"]
