# java-learning

Учебные проекты на Java: алгоритмы, паттерны проектирования и небольшие консольные приложения.
Раньше жили в отдельных репозиториях (`Algorytmes`, `Dijstra`, `DynamicProgramming`, `GreedAlgorytm`, `patterns`, `Stream2`, `ValeraWOW`), теперь собраны здесь вместе с историей коммитов.

| Каталог | Что внутри | Сборка |
|---|---|---|
| [`algorithms/sorting`](algorithms/sorting) | QuickSort и SelectionSort | `javac` |
| [`algorithms/dijkstra`](algorithms/dijkstra) | Алгоритм Дейкстры: поиск кратчайшего маршрута в графе | `javac` |
| [`algorithms/dynamic-programming`](algorithms/dynamic-programming) | Задачи на динамическое программирование | `javac` |
| [`algorithms/greedy`](algorithms/greedy) | Жадные алгоритмы | `javac` |
| [`design-patterns`](design-patterns) | Паттерны GoF: порождающие, структурные, поведенческие | Maven + Lombok |
| [`streams-online-users`](streams-online-users) | Подсчёт максимального числа пользователей онлайн (Stream API) | Maven + Lombok |
| [`valera-wow-game`](valera-wow-game) | Консольная игра-симуляция мира с расами и объектами | Maven + Lombok |

## Требования

- JDK 21+
- Maven 3.9+ (для проектов с `pom.xml`)

## Запуск

Проекты без системы сборки:

```bash
cd algorithms/sorting
javac -d out src/Main.java src/utils/*.java
java -cp out Main
```

Maven-проекты:

```bash
cd design-patterns
mvn compile
```

## Лицензия

[MIT](LICENSE)
