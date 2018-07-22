FROM openjdk:alpine

COPY libs /app/libs/
COPY resources /app/resources/
COPY classes /app/classes/

ENTRYPOINT ["java","-Xmx1024m","-cp","/app/libs/*:/app/resources/:/app/classes/","App"]
CMD []