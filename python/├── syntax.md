# 🐍 Python Синтаксис: базовая шпаргалка

Синтаксис                   | Функционал
============================|===================================================================================
print("текст")              | Вывод на экран
a = 5                       | Присваивание переменной
type(a)                     | Определить тип переменной
input("Введи:")             | Получить ввод от пользователя (всегда str)

# Комментарий               | Комментарии пишутся через `#`

---

## 🔢 Типы данных (базово)

Тип         | Пример
============|==================
int         | 42
float       | 3.14
str         | "hello"
bool        | True / False
list        | [1, 2, 3]
dict        | {"ключ": "значение"}
tuple       | (1, 2)
set         | {1, 2, 3}
NoneType    | None

---

## 📏 Проверка условий

```python
if x > 10:
    print("Больше 10")
elif x == 10:
    print("Ровно 10")
else:
    print("Меньше 10")
