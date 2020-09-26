FROM rust:latest

LABEL maintainer="Alejandro Martinez"

WORKDIR /usr/src/rusteroids

COPY . .

RUN apt-get update && apt-get -y install cmake protobuf-compiler

RUN apt install -y gcc pkg-config openssl libasound2-dev cmake build-essential python3 libfreetype6-dev libexpat1-dev libxcb-composite0-dev libssl-dev libx11-dev  libxcursor-dev libxcursor1 libxrender-dev libxrandr-dev libxi-dev libx11-xcb-dev