# Машин Learning

Блог [m-learn.ru](https://m-learn.ru) для тех, кто хочет начать карьеру Дата Аналитика / Дата Сайнс,
или просто интересуется алгоритмами обработки данных (изображений).
Здесь, я максимально просто пытаюсь объяснить алгоритмы, которые часто используются в
современном мире.

Ваша возможность, сказать мне спасибо - это подписаться на мой 
[телеграм канал](https://t.me/learnm).


## С чего начать?
Для создания среды:

    conda env create -f environment.yml

Для обновления уже существующей среды:
    
    conda env update --name m-learn  --file environment.yml --prune

Для создания кернела в Jupyter:

    conda install ipykernel
    python -m ipykernel install --user --name=m-learn