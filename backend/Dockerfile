FROM openjdk:18
RUN mkdir -p /opt/receptoria
WORKDIR /opt/receptoria
COPY .env /opt/receptoria/.env
COPY recipetoria-backend-0.0.1-SNAPSHOT.jar /opt/receptoria/recipetoria-0.0.1-SNAPSHOT.jar
RUN mkdir -p /opt/receptoria/src/main/resources/static/images
COPY /default_rec/.  /opt/receptoria/src/main/resources/static/images/
EXPOSE 8080
ENTRYPOINT ["java","-jar","/opt/receptoria/recipetoria-0.0.1-SNAPSHOT.jar"]
