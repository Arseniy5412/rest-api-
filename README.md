# Todo App REST API на Go

![Go](https://img.shields.io/badge/Go-1.24-blue)
![Gin](https://img.shields.io/badge/Gin-framework-blue)
![Docker](https://img.shields.io/badge/Docker-ready-blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-blue)

REST API веб-приложение для управления списками задач  
с регистрацией и аутентификацией пользователей.

Проект реализован на **Go** с использованием **Gin**, **PostgreSQL**  
и запускается в **Docker**.

---

## Стек технологий

- **Go 1.24**
- **Gin** — HTTP фреймворк
- **PostgreSQL** — реляционная база данных
- **sqlx** — работа с БД
- **Docker / Docker Compose**
- **JWT** — аутентификация и авторизация
- **Viper** — конфигурация приложения
- **Logrus** — логирование

---

## Реализованный функционал

- Разработка REST API
- Регистрация и аутентификация пользователей
- Работа с JWT
- Middleware для авторизации
- CRUD операции для todo-листов и элементов
- Работа с PostgreSQL
- Написание SQL-запросов вручную
- Генерация и применение SQL-миграций
- Graceful Shutdown HTTP-сервера
- Запуск приложения в Docker

---

### Слои приложения:

- **Handler** — HTTP слой (Gin, обработка запросов)
- **Service** — бизнес-логика приложения
- **Repository** — работа с базой данных (PostgreSQL)
- **Domain** — бизнес-модели и структуры данных
