FROM java:8
VOLUME /tmp
ADD cinema.jar cinema.jar
RUN bash -c 'touch /cinema.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/cinema.jar"]