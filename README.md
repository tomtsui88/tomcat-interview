# tomcat-interview requirement

Tomcat
The Tomcat server is the most widely used open source implementation of the Java Servlet, JavaServer Pages, Java Expression Language, and Java WebSocket technologies. Apache Tomcat software powers numerous large-scale, mission-critical web applications across a diverse range of industries and organizations.

The sample TomCat application (sample.war) will be using for this exercise is included in this git repository.

Objective
You will need to complete the following steps:

a.  Complete the Dockerfile that does the following:
   1.  Move the sample.war to the default deployment (i.e./usr/local/tomcat/webapps) directory
   2.  Expose the default Apache Tomcat server 8080 port
   3.  Launch the Tomcat server by executing catalina.sh
  
b.  Build the Docker image using the Dockerfile (with tag set to 'mywebapp').

c.  Run the container using the Docker image.

d.  Mapping ports from container on to the host machine.

f.  Verify the Tomcat server is running and show us the default webpage (hello.jsp) of the webapp.
