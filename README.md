# PEPEGA
<img src="https://user-images.githubusercontent.com/16631907/82127301-af6d5a00-97dc-11ea-95fe-d2332af00d7b.png" width="300">

> Правильный стандарт PEP для Python.

Этот документ описывает соглашение о том, как писать код для языка Python

PEPEGA создан на основе [PEP8](https://pythonworld.ru/osnovy/pep-8-rukovodstvo-po-napisaniyu-koda-na-python.html) и рекомендациях [ExtremeCode](https://www.youtube.com/channel/UCBNlINWfd08qgDkUTaUY4_w) с добавлениями от Сообщества.


# Оглавление

1. [Внешний вид кода](#Style)

    1.2. [Табуляция или пробелы?](#id1)

    1.3. [Отступы](#id2)

    1.4. [Импорты](#id3)
 

# <a name="Style"></a> Внешний вид кода

### <a name="id1"></a> Табуляция или пробелы?

Табуляция предпочтительна в 9 из 10-и случаев. Пробелы допускаются при поддержке стороннего кода.

### <a name="id2"></a> Отступы

Используйте случайное, в зависимости от ситуации, число пробелов на каждый уровень отступа. Главный принцип руководства - как удобнее, так и делай.

**Правильно**

```python
    foo = long_function_name(var_one, var_two,
                         var_three, var_four)

def long_function_name(
 var_one, var_two, var_three,
                            var_four):
  print(var_one)
```


**Неправильно**

```python
foo = long_function_name(var_one, var_two,
                         var_three, var_four)

def long_function_name(
        var_one, var_two, var_three,
        var_four):
    print(var_one)
```

### <a name="id3"></a> Импорты

Необходимо экономить ГОРИЗОНТАЛЬНОЕ место на мониторе, поэтому умещаем все импорты в одну строку

**Правильно**

```python
import sys, os
```

**Неправильно**

```python
import os
import sys
```

* Импорты нужно размещать в местах перед непосредственным использования модуля.
* Группировать импорты нет смысла
* Рекомендуется использовать шаблоны импортов 
```python 
from import *
```

