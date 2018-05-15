FROM maven:3.3.9-jdk-8

RUN mkdir /src

COPY akka-sample-persistence-java /src/akka-sample-persistence-java

WORKDIR /src/akka-sample-persistence-java

CMD mvn compile exec:java -Dexec.mainClass='sample.persistence.PersistentActorExample'
