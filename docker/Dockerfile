#Download base image ubuntu 16.04
FROM ubuntu:16.04
# Update Ubuntu Software repository
RUN apt-get update
RUN apt-get install -y nginx php7.0-fpm supervisor && \
    rm -rf /var/lib/apt/lists/*
