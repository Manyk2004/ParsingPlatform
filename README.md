# How to Use


- [Бэкенд](#Бэкенд)
  - [Библиотеки](#Библиотеки-бэкенд)
  - [Запуск бэкенд](#запуск-бэкенд)
- [Фронтенд](#Фронтенд)
  - [Библиотеки](#Библиотеки-фронтенд)
  - [Запуск фронтенд](#запуск-фронтенд)
- [Докер Компос](#docker-compose)
  - [Загрузка окружения](#Загрузка-окружения)
  - [Запуск докер компос](#Запуск-докер-компос)


## Бэкенд


### Библиотеки
```bash
cd backend
poetry shell
poetry install
```
### RUN
```
poetry run python src/main.py
```

## Фронтенд


### Библиотеки
```bash
#install npm, node
nvm install 20
cd path_to_front/
npm install
```
### RUN
```
npm run dev
```


# Докер Компос

## Загрузка окружения

1. Создать файл с названием .env.

2. Задать переменным значения:
- Example:
```env
POSTGRES_USER=user 
POSTGRES_PASSWORD=password  
POSTGRES_DB=test 
DB_HOST=db 
DB_PORT=1234
DB_NAME=test 
```

## Запуск докер компос
```bash 
docker compose up --build
```