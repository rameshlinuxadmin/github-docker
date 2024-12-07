FROM httpd
MAINTAINER "Ramesh Aravind"
WORKDIR /usr/local/apache2/htdocs
RUN apt update -y && apt install zip -y && apt install wget -y
RUN wget https://www.free-css.com/assets/files/free-css-templates/download/page296/carvilla.zip
RUN unzip carvilla.zip
CMD ["httpd", "-D", "FOREGROUND"]
