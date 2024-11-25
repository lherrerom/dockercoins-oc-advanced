FROM ruby
RUN gem install sinatra thin
ADD hasher.rb /
CMD ["ruby", "hasher.rb"]
