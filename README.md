# Структура каталога и деплой скрипты для SandyApp

Запуск из консоли: `./start`

Запуск из X-ов (рекомендуется иметь на рабочем столе): `./Sandy_Synday`

Текущая рабочая версия всегда лежит в `./current`

Деплой новой версии (скачает последнюю версию с FTP, распакует и развернет в `./current`):

> ./bin/pull_latest.sh && ./bin/unpack.sh 
