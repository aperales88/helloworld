FROM ${docker.from.image}

EXPOSE 8080

VOLUME /tmp

ADD /maven/helloworld.jar helloworld.jar

ENTRYPOINT ["java","-jar","/helloworld.jar"]