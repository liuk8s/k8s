FROM adoptopenjdk:11-jre-hotspot
RUN mkdir /opt/app
COPY frontend.jar /opt/app
CMD ["java", "-jar", "/opt/app/frontend.jar"]