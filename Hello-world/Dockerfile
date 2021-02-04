# We are using Linux lite distro alpine
FROM openjdk:8
WORKDIR /src/java
COPY . /src/java

# Installing the dependencies
#RUN apk add openjdk8
#ENV JAVA_HOME /usr/lib/jvm/openjdk-1.8-openjdk
#ENV PATH $PATH:$JAVA_HOME/bin

# Compiling the program
RUN javac hello.java

ENTRYPOINT java hello