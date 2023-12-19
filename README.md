# RoadEye
Проект по распознаванию ДТП на дорогах с помощь ИИ

## Кем ведётся разработка проекта
Разработка проекта ведётся Головкиным Матвеем Максимовичем и Галеевой Евгенией Алексеевной

## Использованные технологии:

Язык программирования Python и Jupyter notebook в качестве среды разработки проекта

### Библиотеки и их версии:
 •	Pandas – 1.4.0;
 
 •	Tensorflow , Keras  – 2.6.0, 2.6.0;

 •	Sklearn – 1.1.1;

 •	Numpy – 1.20.0;

 •	PIL – 10.0.1;

 •	CV2 – 4.7.0.72;
 
 •	Matplotlib – 3.5.1.

## Как использовать модели:

Для использования наших моделей необходимо загрузить их по ссылке: https://drive.google.com/drive/folders/1Az4NdWBuBPK0MmFvpvQsW0S5ebZpbJhR?usp=sharing и распаковать папку "Модели" в проект. Также необходимо установить библиотеки из списка выше. После этого открыть файл "result" и в нём вызвать функцию predict_bounding_box(), которая принимает путь до изображения для распознавания.

## Что готово на данный момент

На данный момент наши модели могут отличать машину от иного объекта в близи, а также неплохо распознавать аварии и выделять все обнаруженные объекты в рамки.

## Планы на будущее

• Убрать сжатие изображения при его выводе с разметкой 

• Распознавание и локализация более 1 объекта;

• Увеличение датасета машин и аварий для более лучшего распознавания;

• Работа программы в режиме реального времени.

## Кому может быть полезен наш проект

Наш проект может быть полезен для:
 
 • Муниципальных служб для более быстрого реагирования на ДТП.

 

