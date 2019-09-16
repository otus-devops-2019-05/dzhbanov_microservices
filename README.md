# dzhbanov_microservices
dzhbanov microservices repository

ДЗ №8 (23)
ветка logging-1
- описал fluend, elasticsearch, kibana в docker-compose
- поднял сервисы
- настроил отправку логов в fluentd
- Отредактировали docker/fluentd/fluent.conf для работы с GROK шаблонами. Проверили работоспособность в Kibana. Distributed tracing
- Задал в приложениях режим работы с zipkin: ZIPKIN_ENABLED=true

ДЗ №7
ветка monitoring-2
- Поднял Grafana
- Настроил дашборды
- Настроил алертинг
- Обновил образы


ДЗ№6 
ветка monitoring-1
- Настроил Prometheus
- собрал образ prometheus
- prometheus.yml - описал endpoints
- Проверил работу мониторинга
- добавил сервис node-exporter
- запушил образы в
https://cloud.docker.com/repository/docker/dzhbanov11/prometheus
https://cloud.docker.com/repository/docker/dzhbanov11/post
https://cloud.docker.com/repository/docker/dzhbanov11/comment
https://cloud.docker.com/repository/docker/dzhbanov11/ui
 

ДЗ №5
- Подняшл машину для GITLAB
- Поднял GITLAB в DOCKER
- Настроил pipeline
- Настроил environments
-Настроил дин. окружения



ДЗ №4
-Разобрался  network в docker.
- Запустил проект в двух сетях
- установил docker-compose
- изменил docker-compose.yml 
- вынес переменные
- базовое имя проекта задается директорией. можно использовать ключ -p


ДЗ№3
-Разбил приложение на микросервисы
-Собрал образы
-Оптимизировал UI
-Подключил volume
-убедился в работоспособности

ДЗ№2 
-Установил Docker machine
-Подготовил проект Docker в GCP
-Поднял машину из docker-machine
-Подготовил образ
-Убедился в работоспособности
-Залил на DockerHUB


ДЗ №1 
-Установил докер
-Позапускал контейнеры
-Создал Образ
