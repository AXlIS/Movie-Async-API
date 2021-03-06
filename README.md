# Movie API

## Основные компоненты системы
- PostgreSQL — реляционное хранилище данных.
- Nginx — прокси-сервер, который является точкой входа для веб-приложения.
- Elasticsearch — хранилище данных, в котором лежит вся необходимая информация для сервиса.
- Redis — хранилище данных для кэша.
- Admin — админка для работы с данными 

## Используемые технологии
- FastAPI
- ElasticSearch
- Redis
- Docker
- Pytest
- PostgreSQL
- Gunicorn


## Запуск

```shell
make full_upload
```

## Тестирование
Собрать тестовое окружение и запустить тесты
```shell
make dev_full_upload
make api_tests
```