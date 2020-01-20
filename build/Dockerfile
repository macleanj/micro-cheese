FROM bitnami/nginx:1.16.0

LABEL maintainer="Jerome Mac Lean"
LABEL description="Small microservice application to test Cloud and CICD solutions"

ADD nginx.conf /opt/bitnami/nginx/conf/server_blocks/
ADD ssl/certs/* /opt/bitnami/nginx/conf/server_blocks/ssl/certs/

EXPOSE 8080 8443

ADD www /app
