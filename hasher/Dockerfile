FROM docker.io/library/ruby:alpine
RUN apk add build-base && gem install sinatra && gem install thin && apk del build-base
