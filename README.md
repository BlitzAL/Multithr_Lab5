# Лабораторная работа №5
Запуск

1) Поднять кластер (docker stack deploy ...)
2) Перенести файлы с лабой внуть контейнера (Prepare.bash)
3) Залазим в контейнер-мастер
4) выполняем там Master.bash

После этого можно тестить/запускать лабы.

5) в стендалоне режиме ./Alone.bash task2.py
(spark-submit --master spark://my-hadoop-master:7077 task2.py)
Как пример
в Ярн 
./Yarn.bash task2.py
spark-submit --master yarn --deploy-mode client task2.py
