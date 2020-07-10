FROM openjdk:8-alpine

#COPY target/uberjar/gateway.jar /gateway/app.jar
RUN apt-get update \ 
     apt-get install -y git

RUN git clone https://github.com/pedroaarm/AutomatizatioOfDeployContainersMultiCloud.git

run cd Medical-Center/gateway
#Set working directory

EXPOSE 3000

CMD ["java", "-jar", "/gateway/app.jar"]
