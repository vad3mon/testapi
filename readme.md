### Makefile команды
`make build` Cборка сервисов

`make start` Запуск сервисов

`make stop`  Остановка сервисов

`make restart` Перезапустить сервисы

`make down` Остановить и удалить контейнеры, сети и тома

`make clear` Очистка кэшей

`make migrate` Запустить миграции

`make migrate-concrete name=""` Выполнить миграцию по конкретному названию с параметром name

`make seed` Запустить сиды

`make make-seed name=""` Создать сид с параметром name

`make make-migration name=""` Создать миграцию с параметром name

`make composer-install` Запустить composer install внутри контейнера

`make key-generate` Сгенерировать ключ для приложения

`make composer-update` Запустить composer update внутри контейнера

`make storage-link` Запустить storage link внутри контейнера
