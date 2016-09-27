FROM java:7-alpine
WORKDIR /home/root/java/helloworld
COPY helloworld/src/HelloWorld.java ./src/
RUN mkdir bin && javac -d bin src/HelloWorld.java
WORKDIR /home/root/java/helloworld/bin
CMD ["java", "HelloWorld"]
