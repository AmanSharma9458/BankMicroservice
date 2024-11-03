# FROM openjdk:17-jdk-slim
#
# MAINTAINER eazybytes.com
#
# COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar
#
# ENTRYPOINT ["JAVA", "-JAR", "ACCOUNTS-0.0.1-SNAPSHOT.JAR"]


FROM openjdk:17-jdk-slim

LABEL maintainer="eazybytes.com"

COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java", "-jar", "accounts-0.0.1-SNAPSHOT.jar"]
