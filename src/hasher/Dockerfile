FROM ruby
RUN gem install puma rackup sinatra thin
ADD hasher.rb /
CMD ["ruby", "hasher.rb"]
