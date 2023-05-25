# fill1986_microservices
fill1986 microservices repository

### docker-3
Через docker-mashine в Yancdex Cloud развернут Docker host.
На Docker host запущено приложение которое теперь состоит из трех
компнетов (описаны в ./src) и соответственно контейнеров.
Собраны необходимые образы (ui, post, comment). Для кон. mongo создан Docker volume, чтобы данные не пропадали с остановкой.
Создана bridge-сеть для котейнеров, добавлены сетевые алиаса контейнерам.
Запушены контейнеры в Docker host YC.

### docker-2
Установлен Docker, Docker-machine.
С попощью Docker-machine на VM в Yandex-Cloud запускается docker контейнер из подготовленного образа с БД и приложением.
