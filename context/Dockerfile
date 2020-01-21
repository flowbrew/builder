FROM python:3

RUN apt-get -y update && apt-get -y install \
        apt-utils \
        ruby-full \
        build-essential \
        zlib1g-dev

RUN gem install jekyll bundler jekyll-redirect-from
RUN pip install boto3 requests toolz fn tinify

RUN git config --global user.email "action@flowbrew.ru" && \
    git config --global user.name "GitHub Action"
