FROM ruby:2.6.10
RUN apt-get update -qq && apt-get install -y build-essential nodejs
RUN mkdir /blog
WORKDIR /blog
COPY ./blog/Gemfile Gemfile
COPY ./blog/Gemfile.lock Gemfile.lock
RUN bundle update --bundler && bundle install
COPY ./blog ./blog