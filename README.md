= Пример использования

```cmake
include(${PATH_TO}/add_translations_qt5.cmake)

set(TS_FILES
    translations/ru.ts
    ...
)

add_translations_qt5(TS_FILES ${TS_FILES})
```
