# Олександр | Python & Automation Engineer

[English Version](README.md) | [Русская версия](README_RU.md)

[![Telegram](https://img.shields.io/badge/Telegram-@Blacksamurai1312-2CA5E0?style=flat&logo=telegram)](https://t.me/Blacksamurai1312)
[![Freelancehunt](https://img.shields.io/badge/Freelancehunt-Profile-007ACC?style=flat)](https://freelancehunt.com/freelancer/Blacksamurai1312.html)
[![GitHub](https://img.shields.io/badge/GitHub-ecksecoder-181717?style=flat&logo=github)](https://github.com/ecksecoder)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat&logo=python)](https://www.python.org/)
[![aiogram](https://img.shields.io/badge/aiogram-3.x-2CA5E0?style=flat)](https://docs.aiogram.dev/)
[![SQLite](https://img.shields.io/badge/SQLite-WAL%20Mode-003B57?style=flat&logo=sqlite)](https://www.sqlite.org/wal.html)

---

## Про мене

Інженер-розробник Python, що спеціалізується на проєктуванні високопродуктивних асинхронних бекенд-систем, екосистем Telegram-ботів на базі aiogram 3.x, стійких парсерів даних та інтеграції штучного інтелекту. Основні пріоритети в розробці — захисна архітектура (defensive programming), висока відмовостійкість, неблокуючий асинхронний I/O та стабільна робота під навантаженням.

Ключові компетенції охоплюють створення повнофункціональних Telegram-сервісів з FSM, двосторонню синхронізацію з Google Sheets у реальному часі, каскадні маршрутизатори нейромереж із захистом від вичерпання квот (Google Gemini, Groq), модулі обробки документів та медіа, а також надійні сховища на SQLite у режимі Write-Ahead Logging (WAL).

---

## Приклади реалізованих проєктів

| Проєкт | Стек технологій | Архітектура та можливості | Бізнес-результат |
| :--- | :--- | :--- | :--- |
| **[LeadGen & Booking Bot](https://github.com/ecksecoder/leadgen-booking-bot)** | Python 3.11+, aiogram 3.x, SQLite (режим WAL), Google Sheets API (gspread), Docker | Збір лідів через FSM-сценарії, скоринг контексту (URGENT_VIP, PRICE_INQUIRY, LOW_PRIORITY, STANDARD), інлайн мікро-CRM всередині Telegram, двостороння синхронізація рядків з Google Sheets, тримовний інтерфейс (uk/en/ru). | Автоматична кваліфікація лідів, маршрутизація за SLA, миттєве оновлення звітних таблиць без затримок. |
| **[AI Deal & Lead Radar](https://github.com/ecksecoder/AI-Deal-Lead-Radar)** | Python 3.10+, aiogram 3.x, aiohttp, BeautifulSoup4, feedparser, Google Gemini API, SQLite WAL | Асинхронний фоновий моніторинг, дедуплікація за хешами SHA-256, евристичний та нейромережевий скоринг релевантності, захист від SSRF, ізольовані сповіщення для підписників мовою користувача, експорт у CSV з UTF-8 BOM. | Цілодобовий моніторинг тендерів та замовлень, виключення дублікатів, автоматичне формування звітів для Excel. |
| **[TG Content Summarizer](https://github.com/ecksecoder/tg-summarizer-bot)** | Python 3.10+, aiogram 3.x, Google GenAI SDK, Groq Cloud API, SQLite WAL, pypdf, python-docx | Універсальний крос-мовний хаб аналізу контенту, локальне вилучення тексту з PDF та DOCX, обробка голосових повідомлень через File API, ротація ключів Gemini та аварійний перехід на Groq, черга завдань з пріоритетами. | Багаторівневі саммарі документів та аудіо, автоматичний переклад рідною мовою інтерфейсу, стабільність при відмові API. |

---

## Перелік репозиторіїв

* **[leadgen-booking-bot](https://github.com/ecksecoder/leadgen-booking-bot)**  
  Готовий до комерційного використання Telegram-бот для лідогенерації та запису клієнтів (aiogram 3.x, SQLite WAL, FSM, контексна пріоритизація, двостороння синхронізація з Google Sheets).

* **[AI-Deal-Lead-Radar](https://github.com/ecksecoder/AI-Deal-Lead-Radar)**  
  Асинхронна система моніторингу замовлень, збору лідів та нейромережевого скорингу релевантності для бірж, агрегаторів та закупівельних платформ.

* **[tg-summarizer-bot](https://github.com/ecksecoder/tg-summarizer-bot)**  
  Telegram-бот для автоматичного аналізу та саммаризації публікацій каналів, документів, новинних стрічок, аудіо та веб-статей з використанням Google Gemini API, Groq fallback та SQLite WAL.

---

## Напрямки розробки

* **Розробка Telegram-ботів та екосистем**  
  Проєктування ботів на aiogram 3.x під ключ: складні FSM-ланцюжки, захищені вебхуки, розподіл прав доступу (RBAC), багаторівневі інлайн-меню та кастомні панелі керування.

* **Автоматизація бізнес-процесів та інтеграції**  
  Синхронізація з Google Sheets API v4, підключення CRM-систем, платіжних шлюзів, зовнішніх REST API із забезпеченням ідемпотентності та захисту від дублікатів.

* **Інтеграція AI та LLM-рішень**  
  Впровадження моделей Google Gemini та Groq, семантичний аналіз тексту, автоматична саммаризація, класифікація вхідних запитів, проєктування каскадних відмовостійких систем.

* **Парсинг даних та фоновий моніторинг**  
  Створення асинхронних збирачів даних (aiohttp, BeautifulSoup4, feedparser), валідація URL (anti-SSRF), дедуплікація за контентними хешами та експорт у структуровані звіти (CSV/Excel).

* **Аудит, оптимізація та рефакторинг коду**  
  Усунення блокуючих операцій в event loop, переведення дискових та важких викликів у пул потоків, тюнінг SQLite WAL, оптимізація запитів та контейнеризація у Docker Compose.

---

## Підхід до роботи

* **Захисне програмування (Defensive Programming)**: Валідація даних на зовнішніх межах через Pydantic, сувора типізація, автоматичні повтори (retry) з експоненційним бекофом та плавна деградація функціоналу при збоях зовнішніх сервісів.
* **Неблокуючий асинхронний I/O**: Повний контроль над event loop asyncio. Будь-які синхронні операції або дискові операції виносяться в окремий пул потоків (`asyncio.to_thread`).
* **Високоефективне збереження даних**: Використання SQLite у режимі Write-Ahead Logging (`PRAGMA journal_mode=WAL`), оптимізація синхронізації (`NORMAL`) та обробка блокувань гарантують високу швидкість читання й запису без взаємних колізій.
* **Повна тримовна архітектура**: Нативна підтримка української, англійської та російської мов з чітким розділенням мовних налаштувань між клієнтами та адміністраторами.
* **Продакшн-стандарти та спостережуваність**: Структуроване логування, безпечне керування конфігурацією через змінні оточення (.env), упаковка проєктів у Docker-контейнери.

---

## Зв'язок

* Telegram: [@Blacksamurai1312](https://t.me/Blacksamurai1312)
* Freelancehunt: [freelancehunt.com/freelancer/Blacksamurai1312.html](https://freelancehunt.com/freelancer/Blacksamurai1312.html)
* GitHub: [github.com/ecksecoder](https://github.com/ecksecoder)
