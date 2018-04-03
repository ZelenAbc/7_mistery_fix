# Решатель квадратных уравнений

Решение квадратного уравнения через нахождение дискриминанта.

# Как использовать

Используйте в Python версии 3.5 

`get_roots(a, b, c)`

Где __a__, __b__ и __c__ - коэффициенты квадратного уравнения **ax^2+bx+c=0**

Например:
```python
>>> from quadratic_equation import get_roots
>>> get_roots(1, -2, 1)
(1.0, None)
>>> get_roots(1, 2, -3)
(-3.0, 1.0)
>>> get_roots(1, 0, 25)
(None, None)
```

# Тесты 

Запустить UNIT-тестирование можно следующими способами:

```bash
# possibly requires call of python3 executive instead of just python
$ python tests.py # from parent directory
....
----------------------------------------------------------------------
Ran 4 tests in 0.000s

OK
```

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
