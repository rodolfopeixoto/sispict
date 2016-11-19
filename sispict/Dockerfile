FROM rails:4.2.4
MAINTAINER Rodolfo Peixoto <rodolfo@soulcodejr.com>
RUN mkdir -p /var/app
COPY Gemfile /var/app/Gemfile
WORKDIR /var/app
RUN bundle install
CMD rails s -b 0.0.0.0
CMD rails s -b 0.0.0.0