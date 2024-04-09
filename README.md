# Разработка Нейросетевых Систем
Репозиторий курса Разработка Нейросетевых Систем

### Отчеты

Для **допуска** к экзамену необходимо подготовить отчет по каждой лабораторной и ДЗ. Отчеты по разделам содержат ваши результаты лабораторных работ и ДЗ. Фиксируйте этапы вашей работы, ваши вариации гиперпараметров и моделей, выводы к чему это приводит. На защиту приносите сразу текущую версию отчета.

Отчеты отправлять на почту ``aikanev@bmstu.ru``

## Лекции
[Записи лекций](https://www.youtube.com/watch?v=RkuP6N9Kk5k&list=PLLELLTvDgUQ_d9eUj_3XVpAdGByuU37kT&index=3) Youtube

1. [Лекция №1. Введение в DL](https://github.com/iu5git/Deep-learning/blob/main/lectures/Lection_1_DL.pdf)
2. [Лекция №2. Сверточная нейросеть](https://github.com/iu5git/Deep-learning/blob/main/lectures/Lection_2_CNN.pdf)
3. [Лекция №3. Регуляризация и аугментация](https://github.com/iu5git/Deep-learning/blob/main/lectures/Lection_3_Data_Augmentation.pdf)
4. [Лекция №4. Перенос обучения](https://github.com/iu5git/Deep-learning/blob/main/lectures/Lection_4_Transfer_Learning.pdf)
5. [Лекция №5. Автоэнкодеры](https://github.com/iu5git/Deep-learning/blob/main/lectures/Lection_5_Autoencoders.pdf)
7. [Лекция №6. Сегментация, Object Detection, LiDAR](https://github.com/iu5git/Deep-learning/blob/main/lectures/Lection_7_LiDAR.pdf)
6. [Лекция №7. Рекуррентные нейросети](https://github.com/iu5git/Deep-learning/blob/main/lectures/Lection_6_RNN.pdf)
8. [Лекция №8. Трансформеры](https://github.com/iu5git/Deep-learning/blob/main/lectures/Lection_8_Transformer.pdf)

## Дополнительные лекции
- [Обработка естественного языка](https://github.com/iu5git/Deep-learning/blob/main/lectures/Lection_NLP.pdf)

## Рубежный контроль
1. Рубежный контроль №1 (1-4 лекции)
2. Рубежный контроль №2 (5-8 лекции)

## Лабораторные работы

Выражаем благодарность Ишкову Денису за подготовку лабораторных работ

1. [Лабораторная работа №1](https://github.com/iu5git/Deep-learning/blob/main/notebooks/Lab1.ipynb). Введение в DL
2. [Лабораторная работа №2](https://github.com/iu5git/Deep-learning/blob/main/notebooks/Lab2.ipynb). Сверточная нейросеть
3. [Лабораторная работа №3](https://github.com/iu5git/Deep-learning/blob/main/notebooks/Lab3.ipynb). Регуляризация и аугментация
4. [Лабораторная работа №4](https://github.com/iu5git/Deep-learning/blob/main/notebooks/Lab4.ipynb). Перенос обучения
5. [Лабораторная работа №5](https://github.com/iu5git/Deep-learning/blob/main/notebooks/Lab5.ipynb). Автоэнкодеры
6. [Лабораторная работа №6](https://github.com/iu5git/Deep-learning/blob/main/notebooks/tree_classification.ipynb). Классификация LiDAR
7. [Лабораторная работа №7](https://github.com/iu5git/Deep-learning/blob/main/notebooks/Forest_sat.ipynb). Спутниковые снимки
8. [Лабораторная работа №8](https://github.com/iu5git/Deep-learning/blob/main/notebooks/Lab6.ipynb). Рекуррентные нейросети

## Домашнее задание

### Домашнее задание №1
Согласовать тему с преподавателем. Требуется разработать экспертную систему на основе `SSR` веб-приложения для классификации изображений 3 близких классов. Для этого нужно собрать собственный набор данных, минимум по 100 изображений на класс. Приложение должно выводить загруженное изображение, иметь простой, но индивидуальный дизайн. По каждому классу приложение должно выводить описание и 2-3 ключевых параметра. Например для классификации авиалайнеров выводить описание, количество пассажиров и дальность полета.
- [Web-приложение и сбор датасета](https://github.com/iu5git/Deep-learning/blob/main/homework/homework1.md)

### Домашнее задание №2
Сохраняется тема ДЗ-1. Требуется разработать `SPA` приложение для object detection ваших классов. Разметить изображения набора данных и обучить модель `Yolo`.
- [Инструкция по разметке в cvat.ai](cvat)
- [Приложение на React для onnx YOLO](yolov7_ts)

## Дополнительные материалы
- [Генерация текста](https://github.com/iu5git/Deep-learning/blob/main/notebooks/Text_generation.ipynb)
- [Машинный перевод](https://github.com/iu5git/Deep-learning/blob/main/notebooks/Machine_Translation.ipynb)
- [Телеграм-бот](https://github.com/iu5git/Deep-learning/blob/main/homework2/task.md)


## Вопросы к экзамену
1.	Опишите алгоритм обучения с учителем.
2.	Устройство нейрона, формула вычисления значения. Объясните принцип его работы. 
3.	Многослойный персептрон, архитектура, достоинства и недостатки.
4.	Виды активационных функций, назначение.
5.	Количество нейронов, связей, параметров в полносвязной нейронной сети.
6.	Эпоха, батч, итерация обучения.
7.  Дайте определение функции потерь.
8.	Кросс-энтропия, как функция потерь.
9.	Метод наименьших квадратов, как функция потерь.
10. Алгоритм обратного распространения ошибки.
11.	Алгоритм оптимизации AdaGrad.
12.	Алгоритм оптимизации RMSProp.
13.	Алгоритм оптимизации с моментом.
14.	Алгоритм оптимизации Adam.
15.	Алгоритм оптимизации стохастического градиентного спуска.
16. Преимущества и недостатки стохастического и пакетного градиентного спуска.
17.	Что такое гиперпараметры? Приведите примеры, оптимальные значения гиперпараметров.
18. Оценка точности классификации F1-score, формула расчета и составляющие
19. Что такое ONNX, Pytorch?
20. Опишите структуру набора данных.
21.	Что такое свертка, как она применяется в нейронных сетях?
22.	Свойства свертки.
23.	Количество нейронов, связей и параметров в сверточном слое.
24.	Что такое stride, padding? Варианты.
25. Дайте определение пулинга. Примеры
26. Способы сокращения размерности карты признаков.
27.	Аугментация данных
28.	Переобучение и недообучение нейронной сети.
29.	Дайте определение регуляризации, dropout.
30. Штраф за сложность модели
31. Сглаживание меток
32.	Перенос обучения, дообучение. Принцип, преимущества.
33. Зачем требуется заморозка весов? Применение
34.	Шумоподавляющий автоэнкодер.
35. В чем заключается векторное представление (embedding)? Примеры применения.
36. Сверточный автоэнкодер, применение.
37. Коэффициент детерминации и средняя абсолютная ошибка
38. Преимущества и недостатки современных генеративных моделей
39. Архитектура GAN, обучение.
40. Архитектура VAE, преимущества.
41. Диффузионные модели: принципы, score-функция
42. Архитектура Stable Diffusion
43.	Понятие временного ряда (ВР). Примеры ВР. Цель анализа ВР. 
44.	Опишите задачи регрессии и классификации.
45.	Авторегрессионная модель. Преимущества и недостатки.
46.	Понятие рекуррентных нейронных сетей. Структурная схема RNN.
47.	Особенности обучения рекуррентных нейросетей. Проблема затухающих и взрывных градиентов.
48.	LSTM сети. Преимущества LSTM по сравнению с RNN. 
49.	Количество обучаемых параметров ячейки LSTM в PyTorch
50.	Возможные модификации LSTM. Их преимущества и недостатки.
51.	GRU (Gated recurrent unit) сети.
52.	Применение рекуррентных и LSTM сетей для анализа текста
53. Архитектура seq2seq.
54. Метрики dice и IoU
55. Архитектура PointNet
56. Что такое плотное облако точек? Форматы и особенности обработки
57. Архитектура U-Net
58. Отличие задач сегментации, классификации и обнаружения объектов
59.	Архитектура трансформер
60.	Механизм внимания. Внутреннее и внешнее внимание
61. Архитектуры BERT и GPT