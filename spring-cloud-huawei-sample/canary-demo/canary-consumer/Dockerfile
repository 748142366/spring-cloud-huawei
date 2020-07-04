FROM openjdk:8u181-jdk-alpine

WORKDIR /home/apps/
ADD target/1.3.3-Hoxton-SNAPSHOT .
ADD target/lib ./lib
ADD start.sh .

ENTRYPOINT ["sh", "/home/apps/start.sh"]
