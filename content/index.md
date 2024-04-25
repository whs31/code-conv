---
title: Radar MMS Code Style Guide
tags:
  - c
  - cxx
  - cmake
  - docs
  - code-style
---
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&lgoColor=white)![CMake](https://img.shields.io/badge/CMake-%23008FBA.svg?style=for-the-badge&logo=cmake&logoColor=white)![Qt](https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white)![GitLab CI](https://img.shields.io/badge/gitlab%20ci-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)
# Содержание
## C++
#### **[[C++/cxx-version|Стандарт С++]]**
- **[[C++/cxx-version#Стандарт C++|Используемый стандарт]]**
- **[[C++/cxx-version#Компилятор|Компилятор]]**
- **[[C++/cxx-version#Нестандартные расширения компилятора|Нестандартные расширения языка]]**
#### [[C++/headers|Заголовочные файлы]]
- *[[C++/headers#Расширения файлов|Расширения файлов]]*
- *[[C++/headers#Header-guard|Защита от повторного включения]]*
- *[[C++/headers#Включение других заголовочных файлов|Включение файлов]]*
- *[[C++/headers#Объявления наперед (forward-declarations)|Объявления наперед]]*
- *[[C++/headers#Порядок включений|Порядок включений]]*
#### [[C++/scoping|Область видимости]]
- *[[C++/scoping#Пространства имен|Пространства имен]]*
- *[[C++/scoping#Статические функции|Статические функции]]*
- *[[C++/scoping#Локальные переменные|Локальные переменные]]*
- *[[C++/scoping#Статические и локальные для потока переменные|static и thread_local переменные]]*
#### [[C++/functions|Функции]]
- *[[C++/functions#Входные и выходные параметры|Входные и выходные параметры]]*
- *[[C++/functions#Аргументы по умолчанию|Аргументы по умолчанию]]*
- *[[C++/functions#Синтаксис объявления функции|Синтаксис объявления функции]]*
#### [[C++/lang-features|Возможности C++]]
- *[[C++/lang-features#Rvalue-ссылки|Rvalue-ссылки]]*
- *[[C++/lang-features#Friend|Friend]]*
- *[[C++/lang-features#Исключения и обработка ошибок|Исключения и обработка ошибок]]*
- *[[C++/lang-features#Noexcept|Noexcept]]*
- *[[C++/lang-features#RTTI|RTTI]]*
- *[[C++/lang-features#Приведение типов|Приведение типов]]*
- *[[C++/lang-features#Потоки|Потоки]]*
- *[[C++/lang-features#Префиксный и постфиксный инкремент/декремент|Префиксный и постфиксный инкремент/декремент]]*
- *[[C++/lang-features#Использование const|Использование const]]*
- *[[C++/lang-features#Выражения времени компиляции|Выражения времени компиляции]]*
- *[[C++/lang-features#Целочисленные типы|Целочисленные типы]]*
- *[[C++/lang-features#Макросы|Макросы]]*
- *[[C++/lang-features#Нулевые типы|Нулевые типы]]*
- *[[C++/lang-features#Auto|Auto]]*
#### [[C++/naming|Соглашение по именованию]]
- *[[C++/naming#Файлы|Файлы]]*
- *[[C++/naming#Типы|Типы]]*
- *[[C++/naming#Переменные и константы|Переменные и константы]]*
- *[[C++/naming#Функции|Функции]]*
- *[[C++/naming#Пространства имен|Пространства имен]]*
- *[[C++/naming#Перечисления|Перечисления]]*
- *[[C++/naming#Макросы|Макросы]]*
- *[[C++/naming#Названия библиотек|Названия библиотек]]*
#### [[C++/formatting|Форматирование кода]]
- *[[C++/formatting#Отступы и табуляция|Отступы и табуляция]]*
- [[C++/formatting#Clang-format|Clang-format]]

## CMake
#### [[CMake/commands|Основные команды]]
- *[[CMake/commands#Общая информация|Общая информация]]*
- *[[CMake/commands#Конфигурация|Конфигурация]]*