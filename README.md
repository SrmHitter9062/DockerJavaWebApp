# DockerJavaWebApp
java servlet web app

 1. build app
     - this creates classes in out folder
 2. configure artifacts in app's project structure
 3. build artifacts from build menu
     - this creates war file in out's artifacts folder



$ docker pull image tomcat:latest

$ docker run -d -p 8080:8080 --name myTomcat -v "$(pwd)"/out/artifacts/DockerJavaWebAppWarExploded:/usr/local/tomcat/webapps/ tomcat:latest
