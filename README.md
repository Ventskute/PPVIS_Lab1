# PPVIS_Lab1

В программе был реализован класс прямоугольника (Rectangle) со следующими методами:

* ```setCoordinates``` - задаёт координаты верхней левой вершины
* ```setDimensions```, задаёт ширину и высоту прямоугольника  
* ```checkIfRectangleExists``` проверяет, определён ли прямоугольник, или существует ли прямугольник с текущими значениями  
* ```calcCoordinates``` - высчитывает все координаты прямоугольника, основываясь на координатах верхней левой точки и ширины/высоты  
* ```getData``` выводит на экран схематическое изображение прямоугольника с координатами вершит, значениями ширины, высоты и площади  
* ```changeSize``` увеличивает площадь прямоугольника на заданный пользователем целочисленный множитель  
* ```operator+``` вычисляет наименьший прямоугольник, содержащий два заданных прямоугольника (оператор +)
* ```operator+=``` вычисляет наименьший прямоугольник, содержащий два заданных прямоугольника (оператор +), и присваивает его исходному
* ```operator-``` вычисляет прямоугольник, являющийся общей частью (пересечением) двух прямоугольников (оператор -)
* ```operator-=``` вычисляет прямоугольник, являющийся общей частью (пересечением) двух прямоугольников (оператор -), и присваивает его исходному
* ```operator++``` и ```operator--``` соответственно изменяют размеры прямоугольника по осям X и Y на 1
* ```++operator``` и ```--operator``` соответственно изменяют размеры прямоугольника по осям X и Y на 1; при присваивании возвращают значение перед его изменением
* ```displacement``` задаёт новую левую верхнюю вершину, перемещая прямоугольник по координатной сетке  
