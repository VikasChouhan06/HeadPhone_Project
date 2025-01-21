# Use Tomcat 8.0.15 as the base image
FROM tomcat:8.0.15

# Copy the WAR file from the specified location into Tomcat's webapps directory
COPY ./STQA_Project/dist/STQA_Project.war /usr/local/tomcat/webapps/

# Expose Tomcat's default HTTP port
EXPOSE 8080

# Start Tomcat
CMD ["catalina.sh", "run"]
