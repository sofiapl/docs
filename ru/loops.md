# Циклы

__Цикл__ (_en_ — loop) — это конструкция, позволяющая исполнять один и тот же код переменное количество раз. Все циклы являются утверждениями.

## Цикл `while`

### Синтаксис

```
"while" ["@" <метка>] "(" <условие> ")" <утверждение>
```

### Описание

__Цикл `while`__ — это цикл, выполняющийся пока условие верно.

## Цикл `for`

### Синтаксис

```
"for" ["@" <метка>] "(" <переменная> "in" <итерируемый объект> ")" <утверждение>
```

### Описание

__Цикл `for`__ — это цикл, предназначенный для итерирования над контейнерами и другими итерируемыми объектами.
Итерируемым объектом считается объект типа `Iterable`.
