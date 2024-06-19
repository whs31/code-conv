### Тесты

##### Для написания тестов мы используем фреймворк [GTest](https://github.com/google/googletest).

Тесты хранятся в отдельной  директории:
```
. 
└── math-eigen / 
├── include 
├── src 
├── tests/                # директория с тестами (отдельный проект)
| ├── CMakeLists.txt      # CMakeLists для тестов
| ├── test1.cc            # файл с тестами
| ├── test2.cc            # файл с тестами
└── CMakeLists.txt

```

##### Рассмотрим на примере библиотеки math:

CMakeLists.txt основонго проекта:

```cmake
option(MATH_TESTS "Enable integration tests" OFF) # опция включения тестов
...
if(TESTS)
  enable_testing()
  add_subdirectory(tests)
endif()
...
unset(MATH_TESTS CACHE)
...
```

