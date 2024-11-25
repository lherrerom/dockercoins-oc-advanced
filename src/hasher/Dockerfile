FROM ruby:alpine
RUN apk add build-base && gem install rackup puma sinatra && apk del build-base
ADD hasher.rb /
CMD ruby hasher.rb
