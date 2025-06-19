# ProductManagement1

Spring Boot приложение с использованием Flyway для миграций базы данных. Реализует функционал получения названий продуктов по имени пользователя.

## Функционал
- Миграции БД (`CUSTOMERS` и `ORDERS`) с помощью Flyway.
- REST-эндпоинт `/products/fetch-product?name={name}` для получения списка продуктов (регистронезависимо).
- H2 in-memory база данных.
- Lombok и SOLID-принципы.

## Технологии
- Spring Boot 3.2.5
- Spring JDBC
- Flyway
- H2 Database
- Lombok
- Maven
- Java 17

## Установка и запуск
1. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/art4000xxx/ProductManagement1.git
   Автор
art4000xxx
