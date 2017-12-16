## A tomcat docker image

Based on [anapsix/alpine-java:8_server-jre_unlimited](https://hub.docker.com/r/anapsix/alpine-java/):

* Alpine Linux
* Java Server JRE 8 with unlimited JCE Policy
* Tomcat 8.5

#### How to build?

`docker build -t {YOUR_TAG} .`

#### How to quickstart?

`docker run -it -p 80:8080 {YOUR_TAG}`

Check http://localhost to see the tomcat page.
