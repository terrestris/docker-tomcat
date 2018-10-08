## A tomcat docker image

Based on [openjdk:8-jdk-alpine](https://hub.docker.com/r/library/openjdk/):

* Alpine Linux
* OpenJDK 8
* Tomcat 8.5

#### How to build?

`docker build -t {YOUR_TAG} .`

#### How to quickstart?

`docker run -it -p 80:8080 {YOUR_TAG}`

Check http://localhost to see the tomcat page.
