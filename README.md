<div align="center">

<h1>Бен Абрамян</h1>
<h3>Backend Python Developer (FastAPI / asyncio)</h3>
<p>Москва • Готов к релокации / full remote</p>

<p>
  <a href="https://t.me/rdckk">
    <img src="https://img.shields.io/badge/Telegram-@jisdooo-blue?style=flat&logo=telegram" alt="Telegram">
  </a>
  <a href="https://hh.ru/resume/5ad186cbff0d4d796b0039ed1f62444c326746">
    <img src="https://img.shields.io/badge/HH.ru-Резюме-red?style=flat" alt="HH">
  </a>
</p>

</div>

### Обо мне

- ~6 месяцев коммерческой разработки (+стажировка в Смарт-Софт, продукт компании - Traffic Inspector Next Generation)
- Победитель XI Всероссийской олимпиады по IT/Data Science (1 место из 3000+)
- Люблю чистый, testable и масштабируемый код: **Clean Architecture**, **FastAPI**, **asyncio**, **Pydantic v2**
- Делаю упор на производительность и observability с самого начала проекта

### Ключевые pet-проекты и достижения (pinned ниже)

- **Math Helper** — асинхронный Telegram-сервис для автоматизированного решения математических задач  
  Полноценный продукт: Telegram-бот + backend API + инфраструктура (разработка не окончена)  
  **Стек и архитектура**  
  • FastAPI (асинхронный REST API)  
  • aiogram 3.x (Telegram-бот)  
  • Clean Architecture (слои: routers → services → repositories)  
  • PostgreSQL + SQLAlchemy 2 (async)  
  • Redis (кэширование сессий и часто запрашиваемых решений)  
  • Pydantic v2, asyncio  

  **Ключевые достижения**  
  • Внедрение кэша → снижение нагрузки на PostgreSQL на **60%**   
  • ×2 ускорение добавления новых функций благодаря изоляции бизнес-логики  
  • Реализована **ролевая модель доступа (RBAC)**: разные права для обычных пользователей, премиум, админов, владельца  
  • Настроено структурированное логирование (logging, RotatingFileHandler)  
  • Контейнеризация: Docker + multi-stage builds  

  [→ Репозиторий](https://github.com/wqus/math_service) • [→ Демо бота](https://t.me/math4students_bot)



### Технологии, с которыми работаю комфортно

```text
Язык       │ Python 3.11+ • asyncio
Web        │ FastAPI • Pydantic v2 • aiogram 3
БД         │ PostgreSQL (SQLAlchemy 2 async) • Redis
DevOps     │ Docker • Docker Compose • multi-stage builds
Тестирование│ pytest • pytest-asyncio • Locust
Инструменты│ Git • pre-commit • mypy • ruff • GitHub Actions
Observability │ Loguru • structlog • RotatingFileHandler
Другое     │ REST API • RBAC • Clean Architecture / DDD lite
