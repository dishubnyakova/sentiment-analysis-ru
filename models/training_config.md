# Параметры обучения модели ruBERT-tiny2 tuned

## Базовая модель
`cointegrated/rubert-tiny2`

## Постановка задачи
Классификация эмоциональной окраски русскоязычных коротких текстов на 3 класса:
- negative
- neutral
- positive

## Параметры токенизации
- max_length: 128
- truncation: True
- padding: max_length

## Параметры обучения
- num_train_epochs: 3
- learning_rate: 3e-5
- per_device_train_batch_size: 16
- per_device_eval_batch_size: 16
- weight_decay: 0.01
- fp16: True
- load_best_model_at_end: True
- metric_for_best_model: f1_weighted

## Лучший результат
- Accuracy: 0.7092
- Precision: 0.7081
- Recall: 0.7092
- F1-score: 0.7076
