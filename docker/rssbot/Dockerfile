FROM alpine as builder
WORKDIR /
RUN wget https://github.com/iovxw/rssbot/releases/download/v2.0.0-alpha.9/rssbot-zh-amd64-linux && chmod +x rssbot-zh-amd64-linux

ENTRYPOINT /rssbot-zh-amd64-linux -d /database.json "$TOKEN"