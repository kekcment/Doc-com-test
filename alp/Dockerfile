FROM woahbase/alpine-tomcat
WORKDIR /tmp/
RUN mkdir dta
RUN cp /tmp/dta/ /opt/tomcat/webapps/
CMD ["catalina.sh", "run"]