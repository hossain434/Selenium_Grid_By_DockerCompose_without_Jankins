### Selenium_Grid_By_DockerCompose_without_Jankins
$ docker pull selenium/hub

$ docker pull selenium/node-chrome

$ docker pull selenium/node-firefox

$ docker-compose up -d

$ mvn clean test -Dsurefire.suiteXmlFiles=Testng.xml

$ docker-compose down

#### Reference
https://medium.com/@nitinbhardwaj6/selenium-grid-with-docker-c8ecb0d8404
