# Введение в РС, bash, docker

## Выжимка

1. Введение в РС взяли с курса по РС, презентация - https://github.com/osukhoroslov/distsys-course-hse/blob/master/2022/lectures/01-intro.pdf 

2. bash - используется в терминалах, из важного:
    просмотр файлов (less, cat, head, tail)
    работа с файловой системой (cd, ls, mv, cp, mkdir, touch)
    пайпы (cat a | wc -l)

3. Docker
    "легковесная виртуализация" - контейнеризация
    группа процессов с выделенными ресурсами и неймспейсом, cgroups

## Практика

Можно попрактиковаться с *-seminar.ipynb ноутбуками в образах с ДЗ

## Запись

https://youtu.be/GfIYKt0BgB0

## ДЗ

Docker-ы с заданиями для запуска:

- sindq/lsml-w2-t1-ru:latest
- sindq/lsml-w2-t2-ru:latest
- sindq/lsml-w2-t3-ru:latest
- sindq/lsml-w2-t4-ru:latest
- sindq/lsml-w2-t5-ru:latest
- sindq/lsml-w2-t6-ru:latest
- sindq/lsml-w11-t1-ru:latest
- sindq/lsml-w11-t2-ru:latest
- sindq/lsml-w11-t3-ru:latest
- sindq/lsml-w11-t4-ru:latest
- sindq/lsml-w11-t5-ru:latest

Везде требуется прокинуть порт 8888 (-p 8888:8888)