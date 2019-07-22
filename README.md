RL_UWDC
==============================

Pet project for UWDC

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile для запуска экспериментов
    ├── data               <- Бинарные данные
    │   ├── external       
    │   ├── interim        
    │   ├── processed      
    │   └── raw            
    │
    ├── models             <- Модели из экспериментов
    │
    ├── notebooks          <- Jupyter тетрадки
    │
    ├── references         <- Справка для данных
    │
    ├── reports            <- Отчёты в  LaTeX, etc.
    │   └── figures        <- Картинки для отчётов
    │
    ├── requirements.txt   <- Пакеты для исслоедований
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Исходники в продакшн
    │   ├── __init__.py    
    │   │
    │   ├── data           <- Скрипты для выкачки данных
    │   │   └── make_dataset.py
    │   ├── models        <-  Эксперименты
    │   │   └── run_models.py
    │   │
    │   ├── features       <- Скрипты для предобработки данных
    │   │   └── build_features.py
    │   │
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

