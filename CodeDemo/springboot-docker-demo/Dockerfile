#xác định hình ảnh docker cơ sở

FROM openjdk:17
LABEL maintainer="vanluan"
ADD target/springboot-docker-demo-0.0.1-SNAPSHOT.jar springboot-docker-demo.jar
ENTRYPOINT ["java", "-jar", "springboot-docker-demo.jar"]