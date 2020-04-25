FROM node:latest

RUN npm install -g textlint \
 && npm install -g \
    textlint-rule-preset-japanese \
    textlint-rule-preset-ja-technical-writing \
    textlint-rule-preset-ja-spacing \
    textlint-rule-preset-ja-engineering-paper \
    textlint-rule-preset-jtf-style \
    textlint-rule-prh \
    textlint-rule-ja-space-between-half-and-full-width \
    textlint-rule-ja-space-around-code \
    textlint-rule-ja-hiragana-fukushi \
    textlint-rule-ja-hiragana-keishikimeishi \
    textlint-rule-ja-hiragana-hojodoushi \
    @textlint-ja/textlint-rule-no-synonyms sudachi-synonyms-dictionary

WORKDIR /work

CMD ["textlint", "-h"]
