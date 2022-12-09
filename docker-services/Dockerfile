FROM alpine

RUN echo "Installing redis..."
RUN apk add --update redis

RUN echo "Installing node..."
RUN apk -v --no-cache --update add \
    nodejs-current npm