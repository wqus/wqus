<div align="center">

<h1>Бен Абрамян</h1>
<h3>Backend Python Developer (FastAPI / asyncio)</h3>
<p>Москва • Готов к релокации / full remote</p>

<p>
  <a href="https://t.me/rdckk">
    <img src="https://img.shields.io/badge/Telegram-@jisdooo-blue?style=flat&logo=telegram" alt="Telegram">
  </a>
</p>

</div>

### Обо мне

- ~7 месяцев опыта разработки (включая 1 месяц стажировки в компании Smart Soft, продукт — Traffic Inspector Next Generation)
- Победитель XI Всероссийской олимпиады по IT/Data Science (1 место из 3000+)
- Люблю чистый, тестируемый и масштабируемый код: **Clean Architecture**, **FastAPI**, **asyncio**, **Pydantic v2**
- Делаю упор на производительность и observability с самого начала проекта

**Math Helper** — асинхронный сервис для автоматизированного решения математических задач.  
Полноценный backend-сервис с Telegram-интерфейсом и REST API (разработка завершается).

**Стек и архитектура:**
- FastAPI (асинхронный REST API + веб-часть)
- aiogram 3.x (Telegram-бот)
- Clean Architecture (routers → services → repositories → presenters)
- PostgreSQL + SQLAlchemy 2 (async)
- Redis (кэширование состояний и решений)
- Pydantic v2, asyncio, Docker

**Ключевые достижения:**
- Внедрение Redis-кэша → снижение нагрузки на PostgreSQL на **60%**
- Реализована многослойная архитектура, значительно упростившая добавление новых функций
- Ролевая модель доступа (RBAC): user, premium, admin, owner
- Структурированное логирование и обработка ошибок
- Контейнеризация через Docker (multi-stage builds) + CI/CD

  [→ Репозиторий](https://github.com/wqus/math_service)



### Технологии, с которыми работаю комфортно

```text
Язык       │ Python 3.11+ • asyncio
Web        │ FastAPI • Pydantic v2 • aiogram 3
БД         │ PostgreSQL (SQLAlchemy 2) • Redis
DevOps     │ Docker • Docker Compose • multi-stage builds
Тестирование│ pytest • pytest-asyncio • Locust
Инструменты│ Git • GitHub Actions
Observability │ Loguru • structlog • RotatingFileHandler
Другое     │ REST API • RBAC • Clean Architecture / DDD lite
