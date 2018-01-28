# Multithr_Lab5
Запуск
1) docker ps смотрим id контейнера ( idconn ).
2) docker exec -i -t idconn bash команда что бы залезть в консоль контейнера.
3) Запускаем Prepare.bash на хосте или вручную запускаем скрипты оттуда ( переносим файлы для работы в контейнер)
4) Далее заускаем Master.bash в контейнере ( подготавливаем мастера к работе )
		Если ошибка на /bin/bash^M: bad interpreter
		apt-get install dos2unix
		dos2unix scriptname.bash
5) запуск Alone или Yanr и приписываем что запускать через пробел
