FROM openjdk:11
LABEL author="MaksimAnanev"
WORKDIR /app
COPY calc.java /app/calc.java
RUN javac calc.java
CMD [ "java", "calc" ]