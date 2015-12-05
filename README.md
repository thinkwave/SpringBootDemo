# SpringBootDemo


https://www.youtube.com/watch?v=9JTR7Y_aHuw


1. Demo Source
http://start.spring.io/starter.zip?style=web

2. CodenvySpringBootRunner
FROM codenvy/jdk7
EXPOSE 8080
ENV CODENVY_APP_PORT_8080_HTTP 8080
ADD $app$ /home/user/$app$
WORKDIR /home/user/
RUN unzip $app$ >/dev/null
CMD java -jar application.jar 2>&1 run


