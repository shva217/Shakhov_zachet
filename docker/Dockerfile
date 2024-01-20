FROM php:7.2-apache
WORKDIR /var/www/html
# Copy the app code
COPY . /var/www/html
RUN apt-get update && apt-get upgrade -y && apt-get install -y curl php7.2-mbstring php7.2-zip php7.2-intl php7.2-xml php7.2-json php7.2-curl
RUN echo "Hello, Docker Tutorial"
EXPOSE 80
