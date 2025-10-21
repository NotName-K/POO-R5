# POO-R5
Se modula el programa Shape() en uno y varios modulos
## Opción 1: Modulo Unico
Se establece esta simple estructura:
```markdown
Shape/
│
├── __init__.py
└── shapes.py
```
donde...
```python
# __init__.py
from .point import Point
from .line import Line
from .shape import Shape
from .rectangle import Rectangle
from .square import Square
from .triangle import Triangle
from .isosceles import Isosceles
from .equilateral import Equilateral
from .scalene import Scalene
from .right_triangle import RightTriangle
```
y el modulo unico:
```python
import math

class Point:
....

class Line:
....


class Shape:
....

class Rectangle(Shape):
....

class Square(Rectangle):
....

class Triangle(Shape):
....


class Isosceles(Triangle):
....

class Equilateral(Triangle):
....
```
Opción 2: Modulos Individuales
Se sigue la siguiente estructura:
```markdown
Shape/
│
├── __init__.py
├── point.py
├── line.py
├── shape.py
├── rectangle.py
├── square.py
├── triangle.py
├── isosceles.py
├── equilateral.py
├── scalene.py
└── right_triangle.py
``` 
Donde cada modulo cumple su función sin estar agrupado en un solo archivo con los demás

