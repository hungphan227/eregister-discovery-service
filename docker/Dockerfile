FROM openjdk:8
ADD eregister-discovery-service-1.0.0-SNAPSHOT.jar eregister-discovery-service-1.0.0-SNAPSHOT.jar
# RUN apt-get install vim
# RUN apt-get install telnet
RUN mkdir -p /var/log/eregister-discovery-service && touch /var/log/eregister-discovery-service/eregister-discovery-service.log
CMD java -jar eregister-discovery-service-1.0.0-SNAPSHOT.jar > /var/log/eregister-discovery-service/eregister-discovery-service.log 2>&1
