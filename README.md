# dzhbanov_microservices
dzhbanov microservices repository

ДЗ №12 (28)
Ветка Kubernetes-4
- установил helm
- создал charts для приложения
- Добавил templates
- добавил  _helpers.tpl
- определил переменные
- подготовил итоговую структуру
- прописал values
- обновил релиз. проверил работу приложения
- установил gitlab
- залил приложения в репы
- подготовил .gitla-ci.yml для частей приложения
- запустил проекты, убедился в работоспособности.
- настроил environments, задеплоил



ДЗ №11 (27)
Ветка Kubernetes-3
- настроил Ingress
- Добавил секреты
- Настроил балансировщик
- Network policies, persistent volumes
-  сервис доступен https://34.95.68.65/

ДЗ №10 (26)
Ветка Kubernetes-2
-Установил minikube
- созданы манифесты в kubernetes/reddit/
- настроены mongodb, comment, ui
- созданые services
- Поднял приложения. Намучился с падающими подами и таймаутами при выкачке образов. 
- Развернул в GKE http://34.66.142.157:31092
- Скриншот https://cdn1.savepice.ru/uploads/2019/9/26/5f5184c0c68ca6ac9b3b6480202af0b8-full.jpg



ДЗ №9 (24)
Ветка kubernetes-1
- Прошел the_hard_way. Развернул кластер
- Подготовил описание деплойментов post, ui, comment, mongo
- выполнил kubectl apply, убедился что поды запущены.



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
