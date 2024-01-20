FROM python:3.7.2-alpine3.8
LABEL maintainer="jeffmshale@gmail.com"
RUN apk add --update git
WORKDIR /usr/src/my_app_directory
COPY . .
ARG my_var=my_default_value
ENTRYPOINT ["python", "./app/my_script.py", "my_var"]
EXPOSE 8000
VOLUME /my_volume
