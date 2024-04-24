---
title: 6. Форматирование кода
tags:
  - cxx
---
### Отступы и табуляция
Как и [Google](https://google.github.io/styleguide/cppguide.html#Spaces_vs._Tabs), мы используем **2** пробела на отступ.

Секции области видимости в классах также должны иметь дополнительный отступ в 2 пробела.
Члены пространства имен также должны иметь отступ в 2 пробела.

Пример:
```cpp
namespace ns {
  class Cat {
    public:
      auto meow() -> void;
    private:
      void* data;
  };
}
```