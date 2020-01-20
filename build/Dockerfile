FROM bitnami/nginx:1.16.0

LABEL maintainer="Jerome Mac Lean"
LABEL description="Small microservice application to test Cloud and CICD solutions"

ADD nginx.conf /opt/bitnami/nginx/conf/server_blocks/
# ADD run.sh /run.sh
ADD ssl/certs/* /opt/bitnami/nginx/conf/server_blocks/ssl/certs/

# ENV LISTEN_PORT=80

EXPOSE 80 443
# CMD /run.sh

ADD www /app
