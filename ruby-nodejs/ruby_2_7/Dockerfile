FROM rubylang/ruby:2.7-bionic
RUN apt update && apt install --assume-yes --no-install-recommends curl \
  && curl -sL https://deb.nodesource.com/setup_14.x | bash - \
  && apt update && apt install --assume-yes --no-install-recommends nodejs \
  && rm -rf /var/lib/apt/lists/*
