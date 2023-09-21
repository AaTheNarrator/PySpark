# Задание: Анализ больших данных с использованием PySpark

## Описание задачи
Вы работаете с огромным набором данных о поездках такси в городе. Вам предстоит выполнить следующие шаги, используя PySpark:

1. **Загрузка данных**: Вам дан CSV-файл с данными о поездках такси. Вам нужно загрузить этот файл с использованием PySpark и создать DataFrame.

2. **Подготовка данных**: Проведите предварительный анализ данных и выполните следующие задачи:
   - Удалите дубликаты строк, если они есть.
   - Оцените качество данных и удалите некорректные записи, например, те, у которых отрицательное время поездки или нулевая длительность поездки.

3. **Агрегация и анализ данных**: Используя PySpark SQL, выполните следующие задачи:
   - Рассчитайте среднюю длительность поездки и среднюю стоимость поездки для каждого дня недели.
   - Определите день недели с наибольшей средней стоимостью поездки.

4. **Визуализация данных**: Используя библиотеку Matplotlib или другие инструменты визуализации, создайте графики для следующих данных:
   - График, показывающий динамику средней стоимости поездки по дням недели.
   - График, отображающий распределение длительности поездок.
