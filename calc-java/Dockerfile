FROM openjdk:17-alpine3.14
WORKDIR /app
COPY calc.java /app
RUN javac calc.java
CMD ["java", "calc"]