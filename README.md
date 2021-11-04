# Материалы по C++

## Строка запуска для gcc

```sh
g++ -std=c++11 -Wall -Wextra -O2 {%filename%} -o {%filename.out%}
```

Вариант 2:

```sh
g++ -std=c99 -pipe -O2 -static {%filename%} -o main
```
