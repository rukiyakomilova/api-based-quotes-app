FROM alpine

WORKDIR /opt

COPY import.sh .
COPY mydatabase.sql .


RUN chmod +x import.sh 
RUN apk update && apk add mysql-client  


EXPOSE 3000

CMD /opt/import.sh
#ENTRYPOINT ["/bin/bash", "/import.sh"]
