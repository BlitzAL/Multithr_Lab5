# Лабораторная работа №5
* conf - папка с конфигами
* code - код к 2, 3 и 4 пунктам
Запуск
1) docker ps смотрим имя контейнера
2) docker cp filename 7bb9bfc3511c:/root/filename - копируем имена

docker cp init_master.bash 7bb9bfc3511c:/root/init_master.bash - кописрем имена
docker cp slaves 7bb9bfc3511c:/root/usr/local/spark/conf/slaves - кописрем имена
Если ошибка на /bin/bash^M: bad interpreter
apt-get install dos2unix
dos2unix scriptname.sh

* `prepare-master.bash` - скрипт для настройки мастера, когда стэк поднят
* `init_master.bash` - подготовка мастера к работе (внутри контейнера)
* `standalone.bash` - для запуска кода внутри контейнера в standalone
* `over_yarn.bash` - то же, для over yarn
