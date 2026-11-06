# Александр | Python & Automation Engineer

[English Version](README.md) | [Українська версія](README_UA.md)

[![Telegram](https://img.shields.io/badge/Telegram-@Blacksamurai1312-2CA5E0?style=flat&logo=telegram)](https://t.me/Blacksamurai1312)
[![Freelancehunt](https://img.shields.io/badge/Freelancehunt-Profile-007ACC?style=flat)](https://freelancehunt.com/freelancer/Blacksamurai1312.html)
[![GitHub](https://img.shields.io/badge/GitHub-ecksecoder-181717?style=flat&logo=github)](https://github.com/ecksecoder)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat&logo=python)](https://www.python.org/)
[![aiogram](https://img.shields.io/badge/aiogram-3.x-2CA5E0?style=flat)](https://docs.aiogram.dev/)
[![SQLite](https://img.shields.io/badge/SQLite-WAL%20Mode-003B57?style=flat&logo=sqlite)](https://www.sqlite.org/wal.html)

---

## Обо мне

Инженер-разработчик Python со специализацией на проектировании высокопроизводительных асинхронных backend-систем, экосистем Telegram-ботов на базе aiogram 3.x, отказоустойчивых парсеров данных и интеграции искусственного интеллекта. Главные приоритеты в разработке — защитная архитектура (defensive programming), детерминированная надежность, неблокирующий асинхронный I/O и десятикратный запас масштабируемости.

Ключевые компетенции включают разработку полнофункциональных Telegram-сервисов с FSM, двустороннюю синхронизацию с Google Sheets в реальном времени, каскадные шлюзы нейросетей с защитой от исчерпания квот (Google Gemini, Groq), модули обработки документов и медиа, а также высокопроизводительные хранилища на SQLite в режиме Write-Ahead Logging (WAL).

---

## Примеры решений

| Проект | Стек технологий | Архитектура и функционал | Бизнес-результат |
| :--- | :--- | :--- | :--- |
| **[LeadGen & Booking Bot](https://github.com/ecksecoder/leadgen-booking-bot)** | Python 3.11+, aiogram 3.x, SQLite (режим WAL), Google Sheets API (gspread), Docker | Сбор лидов через FSM-сценарии, контекстный скоринг приоритетов (URGENT_VIP, PRICE_INQUIRY, LOW_PRIORITY, STANDARD), инлайн микро-CRM прямо в Telegram, двусторонняя синхронизация строк с Google Sheets, трехъязычный интерфейс (ru/uk/en). | Автоматическая квалификация лидов, маршрутизация по SLA, мгновенное обновление отчетных таблиц без задержек. |
| **[AI Deal & Lead Radar](https://github.com/ecksecoder/AI-Deal-Lead-Radar)** | Python 3.10+, aiogram 3.x, aiohttp, BeautifulSoup4, feedparser, Google Gemini API, SQLite WAL | Асинхронный фоновый мониторинг, дедупликация по хешам SHA-256, эвристический и нейросетевой скоринг релевантности, защита от SSRF, изолированные оповещения на языке подписчика, экспорт в CSV с UTF-8 BOM. | Круглосуточный мониторинг заказов и тендеров, исключение дубликатов, автоматическая генерация отчетов для Excel. |
| **[TG Content Summarizer](https://github.com/ecksecoder/tg-summarizer-bot)** | Python 3.10+, aiogram 3.x, Google GenAI SDK, Groq Cloud API, SQLite WAL, pypdf, python-docx | Универсальный кросс-языковой хаб анализа контента, локальное извлечение текста из PDF и DOCX, обработка голосовых сообщений через File API, ротация ключей Gemini и аварийный fallback на Groq, очередь задач с приоритетами. | Многоуровневые саммари документов и аудио, автоматический перевод на язык интерфейса, стабильность при сбоях внешних API. |

---

## Репозитории

* **[leadgen-booking-bot](https://github.com/ecksecoder/leadgen-booking-bot)**  
  Готовый к коммерческому использованию Telegram-бот для лидогенерации и записи клиентов (aiogram 3.x, SQLite WAL, FSM, контекстная приоритезация, двусторонняя синхронизация с Google Sheets).

* **[AI-Deal-Lead-Radar](https://github.com/ecksecoder/AI-Deal-Lead-Radar)**  
  Асинхронная система мониторинга заказов, сбора лидов и нейросетевого скоринга релевантности для бирж, агрегаторов и закупочных платформ.

* **[tg-summarizer-bot](https://github.com/ecksecoder/tg-summarizer-bot)**  
  Telegram-бот для автоматического анализа и саммаризации публикаций каналов, документов, новостных лент, аудио и веб-статей с использованием Google Gemini API, Groq fallback и SQLite WAL.

---

## Направления разработки

* **Разработка Telegram-ботов и экосистем**  
  Проектирование ботов на aiogram 3.x под ключ: сложные FSM-сценарии, защищенные вебхуки, ролевая модель доступа (RBAC), многоуровневые инлайн-меню и кастомные панели управления.

* **Автоматизация бизнес-процессов и интеграции**  
  Синхронизация с Google Sheets API v4, подключение CRM-систем, платежных шлюзов, внешних REST API с обеспечением идемпотентности и защиты от повторных операций.

* **Интеграция AI и LLM-инструментов**  
  Внедрение моделей Google Gemini и Groq, семантический анализ текста, автоматическая саммаризация, классификация входящих сообщений, проектирование каскадных отказоустойчивых систем.

* **Парсинг данных и фоновый мониторинг**  
  Создание асинхронных сборщиков данных (aiohttp, BeautifulSoup4, feedparser), валидация URL (anti-SSRF), дедупликация по контентным хешам и экспорт в структурированные отчеты (CSV/Excel).

* **Аудит, оптимизация и рефакторинг кода**  
  Устранение блокирующих операций в event loop, перенос синхронных дисковых вызовов в пул потоков, тюнинг SQLite WAL, оптимизация транзакций и контейнеризация в Docker Compose.

---

## Стандарты работы

* **Защитное программирование (Defensive Programming)**: Валидация данных на границах систем через Pydantic, строгая типизация, автоматические повторы (retry) с экспоненциальным бэкоффом и плавная деградация при сбоях внешних сервисов.
* **Неблокирующий асинхронный I/O**: Полный контроль над event loop asyncio. Любые синхронные библиотеки или операции с файлами изолируются в пуле потоков (`asyncio.to_thread`).
* **Высокопроизводительное хранилище данных**: SQLite в режиме Write-Ahead Logging (`PRAGMA journal_mode=WAL`), синхронизация `NORMAL` и обработка блокировок обеспечивают максимальную скорость чтения и записи без взаимных блокировок.
* **Трехъязычная архитектура**: Нативная поддержка русского, украинского и английского языков с четким разделением языковых настроек между пользователями и администраторами.
* **Продакшн-стандарты и наблюдаемость**: Структурированное логирование, безопасная конфигурация через переменные окружения (.env), декларативное развертывание в Docker Compose.

---

## Контакты

* Telegram: [@Blacksamurai1312](https://t.me/Blacksamurai1312)
* Freelancehunt: [freelancehunt.com/freelancer/Blacksamurai1312.html](https://freelancehunt.com/freelancer/Blacksamurai1312.html)
* GitHub: [github.com/ecksecoder](https://github.com/ecksecoder)
