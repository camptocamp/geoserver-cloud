ARG TAG
FROM geoservercloud/docker-base-java:${TAG}

ARG JAR_FILE=dummy

ADD target/${JAR_FILE} /opt/app/gateway-service.jar

CMD exec java $JAVA_OPTS -jar /opt/app/gateway-service.jar
