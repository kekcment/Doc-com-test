FROM tomcat:9.0
RUN apt update
RUN apt install git maven -y
WORKDIR /tmp/
RUN git clone https://github.com/kekcment/calculator-servlet-example.git
WORKDIR  calculator-servlet-example/
RUN mvn package
RUN cp /tmp/calculator-servlet-example/target/webapps /opt/tomcat/webapps/
EXPOSE 8080