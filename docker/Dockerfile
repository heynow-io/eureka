FROM java:8
VOLUME /tmp

ADD . /usr/app

EXPOSE 9000

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/usr/app/@project.build.finalName@.jar"]
