FROM php:7.2-apache
WORKDIR /var/www/html
# Copy the app code
COPY . /var/www/html
RUN apt-get update && apt-get upgrade -y && apt-get install
RUN echo "Hello, Docker Tutorial"
EXPOSE 80
