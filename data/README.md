# Данные

В проекте использовался датасет **RuSentiTweet** — корпус русскоязычных твитов для задачи sentiment analysis.

Исходный датасет содержит 13 392 твита и 5 классов:
- Positive
- Neutral
- Negative
- Speech Act
- Skip

В рамках данного исследования были оставлены только 3 класса:
- negative
- neutral
- positive

Классы `speech` и `skip` были исключены на этапе предобработки, так как не относятся напрямую к полярности тональности.

## Источники
- GitHub-репозиторий датасета: [RuSentiTweet repository](https://github.com/sismetanin/rusentitweet)
- Статья: Smetanin S. *RuSentiTweet: A Sentiment Analysis Dataset of General Domain Tweets in Russian*. PeerJ Computer Science, 2022.
