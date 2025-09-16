# One Class 100 Tests — v2

Распределение тестов:
- 5 классов × 10 тестов
- 8 классов × 5 тестов
- 10 классов × 1 тест

Каждый тест ~1 секунда (`Thread.sleep(1000)`) и зелёный.

## Структура
```
src/main/java/com/example/App.java
src/test/java/com/example/tests/TenTests01..05.java   (по 10 тестов)
src/test/java/com/example/tests/FiveTests01..08.java  (по 5 тестов)
src/test/java/com/example/tests/SingleTest01..10.java (по 1 тесту)
```
