# Нейросетевой анализатор сетевого трафика
## Настройка рабочего окружения
Установку необходимых пакетов и среды разработки рекомендуется выполнять
в Anaconda (работа выполнялась и тестировалась на anaconda3). Скачать установочный
файл Anaconda можно с официального сайта.

Anaconda сразу содержит в себе среду разработки Jupyter.
Если же Jupyter не установлен в Anaconda, установить можно
при помощи следующей команды:
```
> conda install jupyter
```

Для запуска Jupyter Notebook можно использовать следущую команду:
```
> jupyter notebook
```
## Установка необходимых пакетов
Для работы нейросети необходимы следующие пакеты:
- tensorflow
- keras_spiking
Вспомогательный пакет для считывания датасета:
- pandas
