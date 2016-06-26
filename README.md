# config-server-docker

Get the Github project in your workspace
> git clone https://github.com/debdayal/config-server-docker.git

> cd user-service-docker

> mvn package -DskipTest

> cp target/config-server-1.0.jar docker/

> cd docker

> docker build --force-rm -t debdayal/config-server .

> docker login

> docker push debdayal/config-server

> docker pull debdayal/config-server

> docker run -p 8004:8888 --name config-server -d -t debdayal/config-server --debug




