# Описание функций

В данном разделе представлено описание функций библиотеки `geometric-lib-krugliakov` для вычисления площади и периметра геометрических фигур.

## [Круг](../circle.py)

### `area(r)`

Функция вычисляет площадь круга по заданному радиусу.

**Формула:**

$$
S = \pi r^2
$$

**Пример вызова:**

```python
import circle

result = circle.area(5)
print(result)
```

**Результат:**

```text
78.53981633974483
```

### `perimeter(r)`

Функция вычисляет периметр круга по заданному радиусу.

**Формула:**

$$
P = 2\pi r
$$

**Пример вызова:**

```python
import circle

result = circle.perimeter(5)
print(result)
```

**Результат:**

```text
31.41592653589793
```

---

## [Прямоугольник](../rectangle.py)

### `area(a, b)`

Функция вычисляет площадь прямоугольника по длинам его сторон.

**Формула:**

$$
S = ab
$$

**Пример вызова:**

```python
import rectangle

result = rectangle.area(5, 3)
print(result)
```

**Результат:**

```text
15
```

### `perimeter(a, b)`

Функция вычисляет периметр прямоугольника по длинам его сторон.

**Формула:**

$$
P = 2(a + b)
$$

**Пример вызова:**

```python
import rectangle

result = rectangle.perimeter(5, 3)
print(result)
```

**Результат:**

```text
16
```

---

## [Квадрат](../square.py)

### `area(a)`

Функция вычисляет площадь квадрата по длине его стороны.

**Формула:**

$$
S = a^2
$$

**Пример вызова:**

```python
import square

result = square.area(4)
print(result)
```

**Результат:**

```text
16
```

### `perimeter(a)`

Функция вычисляет периметр квадрата по длине его стороны.

**Формула:**

$$
P = 4a
$$

**Пример вызова:**

```python
import square

result = square.perimeter(4)
print(result)
```

**Результат:**

```text
16
```

---

## [Треугольник](../triangle.py)

### `area(a, h)`

Функция вычисляет площадь треугольника по длине основания и высоте.

**Формула:**

$$
S = \frac{ah}{2}
$$

**Пример вызова:**

```python
import triangle

result = triangle.area(6, 4)
print(result)
```

**Результат:**

```text
12
```

### `perimeter(a, b, c)`

Функция вычисляет периметр треугольника по длинам его сторон.

**Формула:**

$$
P = a + b + c
$$

**Пример вызова:**

```python
import triangle

result = triangle.perimeter(3, 4, 5)
print(result)
```

**Результат:**

```text
12
```
