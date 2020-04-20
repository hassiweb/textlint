FROM node:latest

RUN npm install -g textlint \
 && npm install -g textlint-rule-preset-japanese textlint-rule-preset-ja-technical-writing textlint-rule-prh
WORKDIR /work

ENTRYPOINT ["textlint"]
CMD ["-h"]