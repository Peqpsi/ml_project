# Проект по ML: Предсказание выживаемости на Титанике

## Описание
Проект по машинному обучению, разработанный для освоения продвинутых техник работы с Git. Цель — предсказание выживаемости пассажиров Титаника.

## Основная функциональность
*   Загрузка и предобработка данных (файлы `train.csv`, `eval.csv`).
*   Обучение двух ML-моделей: Логистическая регрессия, Случайный лес и Нейронная сеть с одним скрытым слоем.
*   Конфигурация параметров проекта через `envs/.params.env`.

## Используемые технологии
Python (pandas, scikit-learn, python-dotenv, torch), Git, Jupyter Notebook.

## Запуск проекта

1.  **Клонирование:** `git clone https://github.com/Peqpsi/ml_project.git`
2.  **Окружение:** `python -m venv .venv` и активация (`.venv\Scripts\activate` или `source .venv/bin/activate`).
3.  **Зависимости:** `pip install -r requirements.txt`.
4.  **Данные:** Скачать `train.csv` и `eval.csv` ([Titanic Dataset](https://www.kaggle.com/datasets/syedanabilaakter/titanic-dataset-for-linear-regression-practice?select=train.csv)), поместить в `./data/`. Обновить `envs/.params.env` с путями к этим файлам.
5.  **Выполнение:** Запустить Jupyter (`jupyter lab` или `jupyter notebook`), открыть `main.ipynb` и выполнить все ячейки.

## Демонстрация Git
*   Работа с ветками (`main`, `develop`, `dev_models`, `dev_settings`).
*   Слияние (`git merge`) и разрешение конфликтов.
*   Отмена изменений (`git revert`).
*   Настройка игнорируемых файлов (`.gitignore`).
