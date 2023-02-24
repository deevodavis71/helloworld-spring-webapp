https://github.com/RameshMF/jersey-tutorial/tree/master/helloworld-spring-webapp


Package =

    mvn clean package -Dcheckstyle.skip

    war file will be under target/ folder

Run in Jetty =

    mvn clean package -Dcheckstyle.skip jetty:run

Apache download =

    https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.72/bin/apache-tomcat-9.0.72.zip

    copy war under webapps folder
    cd bin folder under apache root
    sh catalina.sh run
