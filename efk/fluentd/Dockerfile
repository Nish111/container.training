FROM ruby:3.3.7-bookworm
RUN gem install fluentd
RUN gem install fluent-plugin-elasticsearch
COPY fluentd.conf /fluentd.conf
CMD ["fluentd", "-c", "/fluentd.conf"]
