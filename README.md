# netology_virtd34
Задача 1
https://hub.docker.com/repository/docker/fortdragon/netology/general
![image](https://github.com/AntonStogov/netology_virtd34/assets/97850376/43de6285-da29-4df0-9798-bc359955e692)

Задача 2
- Высоконагруженное монолитное Java веб-приложение;
Использование Docker возможно, всё зависит от требований к инфраструктуре, масштабируемости и взаимодействию с другими системами.
- Nodejs веб-приложение;
Лучше всего использовать Docker, он позволяет быстро создавать и тестировать приложения, а также упрощает процесс деплоя. Кроме того, Docker предоставляет инструменты для управления контейнерами и зависимостями, что облегчает разработку.
- Мобильное приложение c версиями для Android и iOS;
Для разработки мобильного приложения с версиями для Android и iOS лучше всего подойдут Docker-контейнеры. Они позволяют быстро создавать и тестировать приложение, а также упрощают процесс развертывания на разных платформах. Кроме того, Docker-контейнеры обеспечивают изоляцию кода и тестирование, а также помогают в управлении зависимостями и конфигурацией проекта.
- шина данных на базе Apache Kafka;
Удобнее всего использовать Docker, т.к это быстро в изоляции, кроме того, Docker облегчает процесс обновления и масштабирования системы, что может быть полезно при росте нагрузки на систему.
- Elasticsearch-кластер для реализации логирования продуктивного веб-приложения — три ноды elasticsearch, два logstash и две ноды kibana;
Из-за простоты управления и сборки контейнеров, мне кажется необходимо распихать продукты по контейнерам и на основании контейнеров собрать кластер стека ELK.
- мониторинг-стек на базе Prometheus и Grafana;
Опять же думаю лучше будет использовать Docker всё по тем же причинам
- MongoDB как основное хранилище данных для Java-приложения;
Зависит от реализации архитектуры приложения. Разница вероятно всего в нагруженности сервиса при большой нагрузке лучше использовать виртуальную машину, при меньшей docker
- Gitlab-сервер для реализации CI/CD-процессов и приватный (закрытый) Docker Registry.
Лучше всего подойдет виртуальная машина или выделенный сервер. Docker Registry требует наличия надежного и быстрого доступа к хранилищу образов, поэтому виртуальная машина или физический сервер будут более предпочтительными.

Задача 3
![image](https://github.com/AntonStogov/netology_virtd34/assets/97850376/e4cbd290-271f-45c4-bbd2-2ad7d20a50f3)

