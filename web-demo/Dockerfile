FROM 192.168.56.105/kubernetes/tomcat:8.0.51-alpine

COPY ROOT /usr/local/tomcat/webapps/ROOT

COPY dockerfiles/start.sh /usr/local/tomcat/bin/start.sh

ENTRYPOINT ["sh" , "/usr/local/tomcat/bin/start.sh"]
