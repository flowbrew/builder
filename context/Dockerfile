FROM python:3

RUN apt-get -y update && apt-get -y install \
    apt-utils \
    ruby-full

RUN gem install jekyll -v 3.8.5 && \
    gem install github-pages -v 203 && \
    pip install awscli
