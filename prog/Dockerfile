FROM tomcat:9.0
RUN apt update
RUN apt install git maven -y
WORKDIR /tmp/
RUN git clone https://github.com/kekcment/calculator-servlet-example.git
WORKDIR  /tmp/calculator-servlet-example
RUN mvn package