### 📚 учебные работы · university labs

лабораторные по анализу данных, машинному обучению и ии с 3 курса бизнес-информатики в мтуси. от основ python до нейросетей, nlp и ии-агентов. всё запускается в google colab
*labs from my 3rd year of business informatics at mtuci: from python basics to neural networks, nlp and ai agents. everything runs in google colab*

`python` `pandas` `scikit-learn` `tensorflow` `keras` `pytorch` `nltk` `spacy` `transformers` `langchain` `opencv`

> отдельные проекты лежат в своих репозиториях: [анализ продаж](https://github.com/nnearss/sales-analytics), [кредитный скоринг](https://github.com/nnearss/credit-scoring), [геоаналитика](https://github.com/nnearss/geo-analytics), [ии-агент](https://github.com/nnearss/vkr-normcontrol-agent)
> *standalone projects have their own repos (links above)*

---

| # | тема · topic | что внутри · what's inside |
|---|---|---|
| 01 | [основы python](01-python-basics/python_basics.ipynb) · *python basics* | строки и срезы, коллекции, циклы, функции на задачах про логи продаж и очистку данных |
| 02 | [pandas и data science](02-pandas-data-science/pandas_data_science.ipynb) · *pandas* | 6 заданий: one-hot кодирование туристов, iris, сводные таблицы, скользящие средние, велопоездки монреаля, world happiness report |
| 03 | [машинное обучение](03-machine-learning/machine_learning.ipynb) · *ml* | логистическая регрессия, knn, k-means, линейная регрессия (boston housing), дерево решений, random forest, mlp |
| 04 | [нейронные сети](04-neural-networks/neural_networks.ipynb) · *neural networks* | нейросеть и rnn с нуля на numpy, dense и cnn на mnist, lstm для отзывов imdb |
| 05 | [обработка текста](05-nlp/nlp.ipynb) · *nlp* | nltk, spacy, natasha, regex, word2vec и fasttext, rnn и lstm, классификация новостей lenta.ru, дообучение bert |
| 06 | [компьютерное зрение](06-computer-vision/computer_vision.ipynb) · *computer vision* | fashion mnist, фильтры собеля и кэнни, карты признаков vgg16 и resnet50, дообучение resnet50 и convnext на датасете одежды |
| 07 | [ии-агенты на langchain](07-langchain-agents/langchain_agents.ipynb) · *ai agents* | lcel-цепочки, промпты и парсеры, память, инструменты, агенты react, rag и гибридный поиск |
| 08 | [data mining](08-data-mining/data_mining.ipynb) | финансовая аналитика, кластеризация страховых клиентов, прогноз расходов, классификация оттока абонентов |
| 09 | [имитационное моделирование](09-simulation-modeling/simulation_modeling.ipynb) · *simulation* | агентная модель рынка, системная динамика эпидемии (seir), дискретно-событийная модель цеха |

---

**как запустить** · *how to run*

откройте нужный ноутбук на github и нажмите «open in colab» или загрузите его в [google colab](https://colab.research.google.com). для 04–06 лучше включить gpu: «среда выполнения → сменить среду → gpu»
*open a notebook in [google colab](https://colab.research.google.com); for 04–06 switch the runtime to gpu*

**данные** · *data*: большинство датасетов скачиваются в коде автоматически. для 03 нужен `boston.csv`, для 08 `Financial Sample.xlsx`, `insurance.csv` и `Churn_binned.csv` из материалов курса, ноутбук сам попросит их загрузить. для 07 нужен ключ openai или совместимого api, его спросят при запуске
*most datasets download automatically. 03 and 08 need course files (the notebook asks for them); 07 asks for an openai-compatible api key at runtime*

---

часть работ сделана по методическим пособиям курса: практикумы г. ю. звездичева (02, 07) и туториалы victor zhou (04). в методичках к 08 и 09 предлагались loginom и anylogic, эти работы я сделала на python
*some labs follow course materials: g. zvezdichev's workbooks (02, 07) and victor zhou's tutorials (04). labs 08 and 09 were designed for loginom and anylogic; i did them in python instead*
