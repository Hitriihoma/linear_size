Тема: Определение линейных размеров прямоугольных участков изображений с помощью библиотеки openCV
Автор: Зубарев Кирилл Николаевич
Цель: Инструмент, который выделяет целевую прямоугольную область на основании цвета и диапазона относителных размеров (если потребуется), определяет её размер и пересчитывает в реальные размеры по коэффициенту масштабирования. 
Масштаб задаётся вводом или в изображении находит "линейку масштаба" и определяет численно пересчёт масштаба изображения к реальному объекту, или метку увеличения и по ней. Но линейка / метка могут быть нанесены ошибочные, так что первоначально ввод. Или просто приведение коэффициентами "найденного размера" к заданному диапазону. 
Необходимо подобрать метод, максимально точно работающий с несколькими известными типами целевых областей.
