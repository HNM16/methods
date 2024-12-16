# Методы строк и математические функции в JavaScript

Добро пожаловать в проект **Методы строк и математические функции в JavaScript**! Этот проект служит руководством для изучения и использования встроенных методов JavaScript для работы со строками и выполнения математических операций.

## 📋 Оглавление
- [Введение](#введение)
- [Методы строк](#методы-строк)
  - [Основные методы строк](#основные-методы-строк)
  - [Примеры](#примеры-использования-методов-строк)
- [Математические функции](#математические-функции)
  - [Основные математические методы](#основные-математические-методы)
  - [Примеры](#примеры-использования-математических-функций)
- [Как использовать](#как-использовать)
- [Как внести вклад](#как-внести-вклад)

---

## Введение
JavaScript предоставляет широкий набор встроенных методов для работы со строками и числами. Методы строк помогают манипулировать текстом и анализировать его, в то время как математические функции используются для выполнения вычислений.

В этом руководстве мы рассмотрим некоторые из самых популярных методов работы со строками и числами в JavaScript, а также приведем примеры их использования.

---

## Методы строк

### Основные методы строк
Вот некоторые из самых часто используемых методов работы со строками:

- **`toUpperCase()`**: Преобразует строку в верхний регистр.
- **`toLowerCase()`**: Преобразует строку в нижний регистр.
- **`includes()`**: Проверяет, содержит ли строка указанную подстроку.
- **`slice(start, end)`**: Извлекает часть строки.
- **`substring(start, end)`**: Похоже на `slice`, но не поддерживает отрицательные индексы.
- **`replace(searchValue, newValue)`**: Заменяет указанный текст на другой.
- **`trim()`**: Удаляет пробелы с начала и конца строки.
- **`split(separator)`**: Разбивает строку на массив подстрок.

### Примеры использования методов строк
```javascript
const text = "   Hello, JavaScript!   ";

console.log(text.length); 
console.log(text.trim()); 
console.log(text.toUpperCase());
console.log(text.toLowerCase()); 
console.log(text.includes("Java")); 
console.log(text.slice(3, 9)); 
console.log(text.replace("JavaScript", "World"));  World!   "


# Math.floor, Math.round, Math.ceil, Math.abs, Math.max, Math.min в JavaScript  
# Math.floor, Math.round, Math.ceil, Math.abs, Math.max, Math.min in JavaScript  

Это руководство посвящено шести основным математическим функциям в JavaScript, которые широко используются при работе с числами.  
This guide focuses on six essential math functions in JavaScript that are widely used for numerical operations.

---

## 📋 Оглавление / Table of Contents  
- [Введение / Introduction](#введение--introduction)  
- [Функции / Functions](#функции--functions)  
  - [Math.floor](#mathfloor)  
  - [Math.round](#mathround)  
  - [Math.ceil](#mathceil)  
  - [Math.abs](#mathabs)  
  - [Math.max](#mathmax)  
  - [Math.min](#mathmin)  
- [Примеры / Examples](#примеры--examples)  
- [Как использовать / How to Use](#как-использовать--how-to-use)  

---

## Введение / Introduction  

Эти шесть функций предоставляют мощные инструменты для работы с числами в JavaScript: округление, нахождение абсолютного значения, а также определение максимального и минимального значения из списка.  
These six functions provide powerful tools for working with numbers in JavaScript: rounding, finding absolute values, and determining maximum or minimum values in a list.

---

## Функции / Functions  

### Math.floor  
- **Описание / Description**:  
  Округляет число вниз до ближайшего меньшего целого.  
  Rounds a number down to the nearest lower integer.  

- **Пример / Example**:  
  ```javascript
  Math.floor(4.9); // Вывод: 4 / Output: 4
  Math.floor(-4.9); // Вывод: -5 / Output: -5
