# Домашнее задание №1

## 1) ANGorbachev-hw01-translation.py
*Переводчик с русского языка на английский. Для перевода используется модель <u>"opus-mt-ru-en"</u> от **Language Technology Research Group at the University of Helsinki**. Модель основана на архитектуре Трансформер и показывает неплохие результаты при не очень больших размерах самой модели (307Мб)*

*Для запуска кода потребуется установка зависимостей:*

```buildoutcfg
pip install transformers sentencepiece sacremoses
```
## 2) khitrin-hw01-NER.py
*Демонстрация возможностей модели [bert-base-NER](https://huggingface.co/dslim/bert-base-NER) из репозитория **HuggingFace**. **BERT** — это семейство языковых моделей, представленное в свет в октябре 2018 г. исследовательской командой из **Google**. В данном случае, как следует из её названия, модель специфически настроена на решение задач **NER** — распознавания именованных сущностей.*

*Для запуска кода потребуется установка зависимостей:*

```buildoutcfg
pip install transformers torch
```
