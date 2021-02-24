FROM openjdk:15

MAINTAINER Philipp Hackner <philipp.hackner@protonmail.com>

ADD target/todo-app-master.jar todo-app-master.jar

CMD [ "sh", "-c", "java -Dserver.port=$PORT -jar /todo-app-master.jar" ]