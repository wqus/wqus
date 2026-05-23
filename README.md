<div align="center">

# Бен Абрамян
### Backend Python Developer (FastAPI / AsyncIO)

Москва • Full Remote / Relocation

<p>
  <a href="https://t.me/rdckk">
    <img src="https://img.shields.io/badge/Telegram-@rdckk-blue?style=flat&logo=telegram" alt="Telegram">
  </a>
  <a href="mailto:3580920@mail.ru">
    <img src="https://img.shields.io/badge/Email-3580920@mail.ru-red?style=flat&logo=gmail" alt="Email">
  </a>
</p>

</div>

---

## Обо мне

Backend-разработчик на Python, специализируюсь на создании асинхронных backend-сервисов и REST API.

Основной стек — **FastAPI**, **AsyncIO**, **SQLAlchemy 2.0**, **PostgreSQL**, **Redis**, **Docker**.  
Люблю production-ready подход: проектирование архитектуры, CI/CD, тестирование и оптимизация производительности.

- Разрабатываю асинхронные сервисы и Telegram-ботов
- Использую Clean Architecture и многослойный подход
- Пишу тестируемый и масштабируемый код
- Интересуюсь highload/backend engineering и инфраструктурой
- Победитель Всероссийской олимпиады «Актионада» (IT / Data Science, 2025)

---

# Ключевые проекты

## Math Helper
Асинхронный Telegram-бот для решения математических задач с использованием локальных LLM.

### Что реализовано

- Полностью асинхронный backend на Python + aiogram 3.x
- Архитектура по принципам Clean Architecture
- PostgreSQL + SQLAlchemy 2.0 + Alembic
- Redis для кэширования и хранения состояний
- RBAC (user / premium / admin / owner)
- Rate limiting и ticket system
- Монетизация через Telegram Stars
- Docker + Docker Compose
- CI/CD через GitHub Actions
- Unit + integration тесты
- Интеграция локальных LLM через Ollama

### Инженерные решения

- Stateless-архитектура с вынесением состояния в Redis
- Подготовка сервиса к горизонтальному масштабированию
- Структурированное логирование и централизованная обработка ошибок
- Production-ready организация проекта и инфраструктуры

[→ Репозиторий проекта](https://github.com/wqus/math_service)

---

## Finly REST API

REST API для управления личными финансами.

### Основные возможности

- JWT authentication (access/refresh tokens)
- CRUD для финансовых операций
- Многослойная архитектура API → Services → Repositories
- PostgreSQL + SQLAlchemy 2.0 + Alembic
- Docker + CI/CD pipeline
- Асинхронный FastAPI backend

[→ Репозиторий проекта](https://github.com/wqus/finly-api)

---

## Device Statistics Analytics API

Backend-сервис для сбора и аналитики статистики устройств.

Проект разработан в рамках технического отбора на стажировку «ДИП:КОД» от Газпром нефти.

### Что реализовано

- REST API на FastAPI
- Аналитика: min/max/count/sum/median
- Фильтрация по временным периодам
- Нагрузочное тестирование через Locust
- Оптимизация PostgreSQL-запросов индексами
- Docker + Alembic migrations

[→ Репозиторий проекта](https://github.com/wqus/dip_code_test_api)

---

# Технологии

```text
Backend:
Python 3.12, FastAPI, AsyncIO, aiogram 3.x

Databases & Infra:
PostgreSQL, SQLAlchemy 2.0, Redis,
Docker, Docker Compose, Alembic

Engineering:
REST API, Clean Architecture,
CI/CD (GitHub Actions),
Pytest, Git/GitHub

Performance & Ops:
Locust, Logging, Linux

Additional:
Ollama, LLM integration
