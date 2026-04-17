<div align="center">

<h1>Бен Абрамян</h1>
<h3>Backend Python Developer (FastAPI / asyncio)</h3>
<p>Москва • Готов к релокации / full remote</p>

<p>
  <a href="https://t.me/rdckk">
    <img src="https://img.shields.io/badge/Telegram-@rdckk-blue?style=flat&logo=telegram" alt="Telegram">
  </a>
</p>

</div>

### Обо мне

- 8 месяцев опыта разработки (включая 1 месяц стажировки в компании Smart Soft, продукт — Traffic Inspector Next Generation)
- Победитель XI Всероссийской олимпиады по IT/Data Science (1 место из 3000+)
- Люблю чистый, тестируемый и масштабируемый код: **Clean Architecture**, **FastAPI**, **asyncio**, **Pydantic v2**
- Делаю упор на производительность и observability с самого начала проекта

### Ключевой проект:
Math Helper - асинхронный backend-сервис для решения математических задач с использованием локальных LLM

**Стек и архитектура:**
- aiogram 3.x (Telegram-бот)
- Clean Architecture (routers → services → repositories → presenters)
- PostgreSQL + SQLAlchemy 2 + alembic (async)
- Redis (кэширование состояний и решений)
- asyncio, Docker
- Git, CI/CD
- Ollama
- logging, JSON, RotatingFileHandler

**Ключевые достижения:**
- Спроектировал stateless-сервис с вынесением состояния в Redis для горизонтального масштабирования
- Реализована многослойная архитектура, значительно упростившая добавление новых функций
- Ролевая модель доступа (RBAC): user, premium, admin, owner
- Структурированное логирование и обработка ошибок
- Настроил CI/CD (GitHub Actions): сборка и деплой сервиса (Docker, zero-downtime)
- Интегрировал локальные LLM (через Ollama) с отказоустойчивой обработкой 

  [→ Репозиторий](https://github.com/wqus/math_service)



### Технологии, с которыми работаю комфортно

```text
Языки и фреймворки: Python 3.11+ (Asyncio), FastAPI, Pydantic v2, aiogram 3.x, Ollama.
Базы данных и Infra: PostgreSQL (SQLAlchemy, Alembic), Redis, Docker, Docker Compose.
Инженерия: REST API, Clean Architecture (DDD), Git (PR, Code Review), Unit-тесты (Pytest), Mypy, CI/CD (GitHub Actions).
Сетевые технологии: Модель OSI, TCP/IP, HTTP/S, настройка правил фильтрации трафика и проброса портов.
QA & Мониторинг: системное логирование (Loguru, logging, JSON, RotatingFileHandler).
ML / Data Science: pandas, numpy, sklearn (олимпиадный опыт)
