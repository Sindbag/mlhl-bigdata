# MLHL: Big Data курс

## Формула оценки

    min(10, 0.6 ДЗ + 0.4 проект + 0.3 бонусы)

[Страница с оценками](https://docs.google.com/spreadsheets/d/158tztQ-jFFErWMk7k3INnSs8tjDTWP9j1SBE-uxFfMw/edit?usp=sharing)

[Канал в телеграмме](https://t.me/+7c_vSRhfV102YWFi)

[Wiki](https://clck.ru/326SeW)

[Плейлист](https://clck.ru/326SgG)


Занятия проходят в Zoom - https://us06web.zoom.us/j/84811522468?pwd=aWFQSHJUdzFOYm5ETSthMlhTcEVrZz09 **по пятницам в 19:00**

## Лекторы

Бардуков Анатолий Андреевич - tg: @sindq

Свиридов Иван

Соозарь Мария

## План курса

детали по каждому пункту лежат в соответствующих папках

1. Введение в РС + Bash & Docker
2. SQL, NoSQL, MPP - знакомство с видами БД + синтаксис запросов
3. ------------
4. YARN + HDFS + MapReduce
5. Spark RDD
6. Spark DataFrame + Spark SQL
7. Spark ML + handcrafted ML on Spark
8. MLOps (model to docker to prod + balancer) + MLFlow
9. Distributed Learning + Quantization + Distillation + Prunning
10. Approx answer searching - LSH + HNSW
11. Streaming (Spark + Kafka)
12. Flink
13. ETL (Airflow) + DWH
14. Vertica
15. Data Vault

---

После НГ - занятия про РС:
1. highload + load balancing
2. concurrency + consistency
3. CPU-bound + IO-bound
4. architecture interview example


### Сдача заданий

Специфичные инструкции по сдаче есть в каждой теме, но базово подход такой:
1. запускаете Docker-контейнер по выбранной теме


        docker run -d -p <local>:<container> sindq/lsml-w<N>[-<task>]-ru

    Например: `docker run -d -p 8080:80 sindq/lsml-w4-ru:latest`


2. решаете задание в контейнере, в результате получаете некоторый файл с решением (в контейнере)
3. делаете специфический запрос в грейдер (параметры - задание, ваш идентификатор (аккаунт в тг), номер задания, решение (тело post запроса))

        curl -F @filename <IP>/<COURSE>/<USER>/w<N>/<task>

        curl -F file=@result.json 51.250.54.133/MLHL-LSML/sind/w7/1

4. получаете оценку, она автоматически сохраняется в документ с оценками (сохраняется не лучшая, а последняя попытка, комментарии к ячейке будут содержать доп информацию)
5. результат запроса также содержит оценку и комментарий

## Бонусные задания
Каждое защищённое задание даёт 1 балл от итоговой оценки.

По своей сути они похожи на архитектурные собеседования, у вас будет 25 минут на презентацию вашего решения
(обычно даётся 1 час, но и решается задание на месте)

### Процесс сдачи
Устная защита решения, которое вы прорабатываете самостоятельно:

- выбираете тему
- придумываете решение, примерные критерии будут описаны в самом задании
- договариваетесь о дате созвона с кем-то из преподавателей
- звонок длится ~40 минут (15 минут закладываем на вопросы, постановку и общение на смежные темы)
- получаете оценку :)

### Темы

1. TBA
2. TBA
3. TBA