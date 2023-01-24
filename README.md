# CV_Lab2
<!DOCTYPE html>
<html>
<head> 
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
## Лабораторная 3: Классификация изображений на основе сверточных нейронных сетей
</head>
<body>
<h1>Задание</h1>
<p>
- 1. Реализовать систему классификации согласно описанию, используя не
     менее трех различных архитектур нейронной сети.</p>
<p>
- 2. Сравнить качество работы, скорость и количество потребляемой памяти
     для каждой архитектуры.
</p>
<p>
- 3. Сделать отчёт в виде readme на GitHub, там же должен быть выложен
     исходный код.
</p>
<h1>Теоретическая база</h1>
<p>Классификация изображений – это процесс извлечения классов информации из многоканального растрового изображения. Растр, полученный в результате классификации изображения, можно использовать для создания тематических карт.
</p>
<p>
В зависимости от характера взаимодействия аналитика с компьютером в процессе классификации, различают два
типа классификации изображений: классификацию с обучением и классификацию без обучения.
</p>
<h2>AlexNet</h2>
<p><img src="https://github.com/AlexVasilkina/CV_Lab3/blob/main/AlexNet.png?raw=true"></p> 
<h2>ResNet</h2>
<p><img src="https://github.com/AlexVasilkina/CV_Lab3/blob/main/resNet.png?raw=true"></p> 
<h2>VGG16</h2>
<p><img src="https://github.com/AlexVasilkina/CV_Lab3/blob/main/vgg16.png?raw=true"></p> 
<h1>Описание разработанной системы</h1>
<p>Была реализована простейшая система классификации изображений на основе сверточных нейронных сетей.
</p>
<p>Система загружает изображения с диска, преобразовывает в нужный для обработки моделью нейронной сети формат (тензор), выполеяет предобработку и обрабатывает с помощью нейронной сети и выводит результат.
</p>
<h1>Выводы по работе</h1>
<p>
Результат работы сетей представлен ниже:

| accuracy   | vgg    | alexnet | resnet50 |
|------------|--------|---------|----------|
| top1       | 0.84   | 0.72    | 0.88     |
| top5       | 1.0    | 0.8     | 1.0      |

Как видно из результатов работы, наибольшей точностью обладает сеть resnet50.
</p> 
<h1>Использованные источники</h1>
<p>https://pytorch.org/vision/stable/models.html</p> 
<p>https://towardsdatascience.com/alexnet-the-architecture-that-challenged-cnns-e406d5297951</p> 
<p>https://habr.com/ru/company/nix/blog/430524/</p>
</body>
</html>
