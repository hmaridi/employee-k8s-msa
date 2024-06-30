FROM openjdk:17-alpine
ENV APP_FILE employee-service-1.1.jar
ENV APP_HOME /usr/apps
EXPOSE 8092
COPY target/$APP_FILE $APP_HOME/
WORKDIR $APP_HOME
ENTRYPOINT ["sh", "-c"]
CMD ["exec java -jar $APP_FILE"]