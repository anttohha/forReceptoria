FROM openjdk:18
RUN mkdir -p /opt/receptoria
WORKDIR /opt/receptoria
COPY .env /opt/receptoria/.env
COPY /target/recipetoria-backend-0.0.1-SNAPSHOT.jar /opt/receptoria/recipetoria-0.0.1-SNAPSHOT.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/opt/receptoria/recipetoria-0.0.1-SNAPSHOT.jar"]
