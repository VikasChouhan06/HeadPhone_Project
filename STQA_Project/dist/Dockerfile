# Use Tomcat 8.0.15 as the base image
FROM tomcat:8.0.15-jre8

# Maintain image metadata
LABEL maintainer="VikasChouhan06"

# Set environment variables for Tomcat
ENV CATALINA_HOME /usr/local/tomcat
ENV PATH $CATALINA_HOME/bin:$PATH

# Copy the WAR file from the local machine to the Tomcat webapps directory
# Replace 'your-app.war' with the name of your WAR file
COPY STQA_Project.war $CATALINA_HOME/webapps/

# Expose Tomcat's default HTTP port
EXPOSE 8080

# Start Tomcat when the container runs
CMD ["catalina.sh", "run"]
