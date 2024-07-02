FROM openjdk:17-alpine
ENV APP_FILE organization-service.jar
ENV APP_HOME /usr/apps
EXPOSE 8093
COPY target/$APP_FILE $APP_HOME/
WORKDIR $APP_HOME
CMD ["exec java -jar $APP_FILE"]