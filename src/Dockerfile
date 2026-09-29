FROM tomcat:10.1-jdk21-temurin

# Remove Tomcat's default application
RUN rm -rf /usr/local/tomcat/webapps/*

# Copy your WAR file
COPY myapp.war /usr/local/tomcat/webapps/ROOT.war

# Tomcat listens on 8080
EXPOSE 8080

# Start Tomcat
CMD ["catalina.sh", "run"]
