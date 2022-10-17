# Spark - фреймворк для распределённых вычислений

## Выжимка

Реализован на Scala, имеет несколько реализаций: SparkR, PySpark

1. Spark RDD - основа всех вычислений
    - resilent distributed dataset (восстановимый)
    - является DAG - directed acyclic graph
    - создание RDD - из файла, Python-коллекции или другого RDD
    - можно достраивать DAG - трансформации
    - запуск вычислений - action
    - дополнительные возможности - cache, persist
2. Spark SQL
    - Spark DataFrame API - Pandas-like ООП подход
    - Spark SQL - HiveQL - SQL-подобный подход
    - компилируется через Catalyst оптимизатор
    - на низком уровне оперирует RDD
    - можно преобразовать к RDD и обратно с помощью объекта Row
3. Остальные возможности фреймворка
    - библиотека SparkML для работы с ML
    - библиотека Spark GraphX для работы с графами
    

## Практика

семинарские ноутбуки в образах с ДЗ

## Запись

https://www.youtube.com/watch?v=_8TeUlJSJEQ&list=PLmA-1xX7IuzAcOe1hOaDW8Jj4mVaLOoDD

## ДЗ

Докеры для ДЗ:

- sindq/lsml-w4-ru:latest