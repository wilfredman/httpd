FROM httpd:2.4
MAINTAINER wilfred_t_man@manulife.com
ENV MS_NAME 'myhttpd'
ENV JAVA_VER 8
ENV VERSION '0.0.1'

COPY ./html /usr/local/apache2/htdocs/html
COPY ./conf /usr/local/apache2/conf

EXPOSE 80