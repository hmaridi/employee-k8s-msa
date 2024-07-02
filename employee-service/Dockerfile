FROM openjdk:17-alpine
ENV APP_FILE employee-service-1.2.jar
ENV APP_HOME /usr/apps
EXPOSE 8092
COPY target/$APP_FILE $APP_HOME/
WORKDIR $APP_HOME
CMD ["exec java -jar $APP_FILE"]