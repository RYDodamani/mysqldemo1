FROM mysql:9.2.0
ENV MYSQL_ROOT_PASSWORD=my-secret
ENV MYSQL_DATABASE=mydb
RUN microdnf install -y git && microdnf clean all
EXPOSE 3306