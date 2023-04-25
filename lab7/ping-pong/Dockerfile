FROM openjdk:8-jdk-slim
COPY PingPongHudoba.java /
RUN javac PingPongHudoba.java 
EXPOSE 8080
ENTRYPOINT ["java"]
CMD ["PingPongHudoba"]
