# Transformer Implementation

Ручная имплементация архитектуры Transformer без использования высокоуровневых библиотек.

## Цель проекта

Понять, как работает архитектура Transformer «изнутри».

## Функции

- Positional Encoding
- Scaled Dot-Product Attention
- Multi-Head Attention
- Encoder & Decoder
- Финальная модель Transformer
- Токенизатор
- Обучение на игрушечном датасете (перевод с французского на английский)

## Пример

```
Input: je suis étudiant
Output: i am a student
```

## Как запустить

```bash
pip install torch numpy
```

Запустить ноутбук:

```bash
jupyter notebook transformer_implement.ipynb
```

## Возможные улучшения

- Разделение на модули
- Attention visualization
- Расширение датасета

## Источники

- [Attention is All You Need](https://arxiv.org/abs/1706.03762)
- [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
