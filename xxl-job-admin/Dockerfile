#FROM openjdk:8-jre-slim
#MAINTAINER xuxueli
FROM docker.abcpen.com/zmeet-prd/agent-base:1.0.0
WORKDIR /app
ENV JAVA_OPTS=""
ENV LANG="en_US.UTF-8"
COPY ./xxl-job-boot-*.jar  /app/xxl-job.jar
ENTRYPOINT java ${JAVA_TOOLS_OPTS} ${JAVA_OPTS} -jar /app/xxl-job.jar