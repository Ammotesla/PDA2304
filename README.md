# Практическая работа №1
## Тема: "Разработка графического интерфейса по макетам"

### Цель работы: повторить графический интерфейс макетов, используя базовые знания языка программирования dart

### Ход работы:
На выбор было предоставлено пять макетов:
<p align="center">
  <img src="/layout_imgs/layouts.PNG"/>
</p>
Три из которых были выбраны для повторения:

1. Макет №2;
2. Макет №3;
3. Макет №4.

Первый макет. Для его создания были использованы следующие виджеты: Container, Row, Column, Expanded, Text, Icon, ListView, а также MaterialApp и Scaffold. Для закругления углов контейнеров был использован класс BoxDecoration, а для разделения элементов ListView использовался его метод .separated.

Результат:
<p align="center">
  <img src="/layout_imgs/layout1.png"/>
</p>

Второй макет. Для его создания были использованы такие же виджеты, что и для первого макета, но с добавлением пары новых, например, виджеты Card для создания красивых элементов-карточек, Padding, а также SingleChildScrollView для горизонатального скроллинга элементов. Самая большая сложность в этом макете, как и во всей практчиеской в целом, на решение которой ушло 3 дня, было решение поместить ListView с горизонтальным скроллингом в ListView, который возвращался в методе build, в следствие чего вылетала ошибка разметки. Решение оказалось очень простым. Вместо использования второго ListView было принято решение использовать SingleChildScrollView. 

Результат:
<p align="center">
  <img src="/layout_imgs/layout2.png"/>
</p>

Третий макет. Для его создания были использованы всё те же виджеты, что и для первого макета, только в виджет Scaffold был добавлен параметр backgroundColor для изменения цвета заднего фона всего окна.

Результат:
<p align="center">
  <img src="/layout_imgs/layout3.png"/>
</p>

### Вывод: в данной практической работе были сделаны три макета окон приложения с помощью базовых знаний языка программирования dart.
