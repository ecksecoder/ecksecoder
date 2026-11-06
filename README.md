# Alexander | Python & Automation Engineer

[Українська версія](README_UA.md) | [Русская версия](README_RU.md)

[![Telegram](https://img.shields.io/badge/Telegram-@Blacksamurai1312-2CA5E0?style=flat&logo=telegram)](https://t.me/Blacksamurai1312)
[![Freelancehunt](https://img.shields.io/badge/Freelancehunt-Profile-007ACC?style=flat)](https://freelancehunt.com/freelancer/Blacksamurai1312.html)
[![GitHub](https://img.shields.io/badge/GitHub-ecksecoder-181717?style=flat&logo=github)](https://github.com/ecksecoder)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat&logo=python)](https://www.python.org/)
[![aiogram](https://img.shields.io/badge/aiogram-3.x-2CA5E0?style=flat)](https://docs.aiogram.dev/)
[![SQLite](https://img.shields.io/badge/SQLite-WAL%20Mode-003B57?style=flat&logo=sqlite)](https://www.sqlite.org/wal.html)

---

## Overview

Software engineer specializing in high-throughput asynchronous backend systems, Telegram bot ecosystems (aiogram 3.x), resilient web scraping pipelines, and autonomous AI integrations. Engineering approach centers on defensive programming, zero-downtime reliability, non-blocking asynchronous architectures, and deterministic data handling under volatile real-world traffic.

Key competencies include end-to-end bot development with stateful Finite State Machines (FSM), real-time Google Sheets two-way synchronization, multi-provider LLM failover routers (Google Gemini, Groq), content ingestion pipelines (documents, RSS, audio), and high-efficiency persistence using SQLite in Write-Ahead Logging (WAL) mode.

---

## Featured Solutions

| Solution | Technology Stack | Core Architecture & Features | Production Capabilities |
| :--- | :--- | :--- | :--- |
| **[LeadGen & Booking Bot](https://github.com/ecksecoder/leadgen-booking-bot)** | Python 3.11+, aiogram 3.x, SQLite (WAL mode), Google Sheets API (gspread), Docker | Structured lead intake via FSM, context triage scoring (URGENT_VIP, PRICE_INQUIRY, LOW_PRIORITY, STANDARD), in-Telegram manager micro-CRM, two-way Google Sheets row synchronization, trilingual client UI (en/uk/ru). | Automated lead qualification, SLA routing, dynamic localized CRM cards, real-time spreadsheet updates. |
| **[AI Deal & Lead Radar](https://github.com/ecksecoder/AI-Deal-Lead-Radar)** | Python 3.10+, aiogram 3.x, aiohttp, BeautifulSoup4, feedparser, Google Gemini API, SQLite WAL | Asynchronous background polling worker, SHA-256 fingerprint deduplication, heuristic and neural relevance scoring, anti-SSRF validation, subscriber-isolated localized push alerts, Excel-compatible UTF-8 BOM CSV exports. | 24/7 opportunity aggregation, zero-duplicate intake, multi-channel RSS/HTML scraping, dynamic reporting. |
| **[TG Content Summarizer](https://github.com/ecksecoder/tg-summarizer-bot)** | Python 3.10+, aiogram 3.x, Google GenAI SDK, Groq Cloud API, SQLite WAL, pypdf, python-docx | Universal cross-lingual synthesis hub, local document extraction (PDF, DOCX, TXT), audio ingestion via GenAI File API, Gemini Flash key-rotation with Groq llama-3.3-70b failover, priority task queue, sliding-window raw storage hygiene. | Multi-tier executive summaries, multilingual document synthesis, quota-exhaustion fallback, safe web parsing. |

---

## Featured Repositories

* **[leadgen-booking-bot](https://github.com/ecksecoder/leadgen-booking-bot)**  
  Production-ready LeadGen and Booking Telegram Bot built with aiogram 3.x, SQLite (WAL mode), FSM, context triage, and Google Sheets bidirectional synchronization.

* **[AI-Deal-Lead-Radar](https://github.com/ecksecoder/AI-Deal-Lead-Radar)**  
  Production-grade asynchronous deal monitoring, lead ingestion, and neural relevance scoring system for freelance platforms, procurement portals, and B2B aggregators.

* **[tg-summarizer-bot](https://github.com/ecksecoder/tg-summarizer-bot)**  
  Production-ready Telegram AI Bot for summarizing channel posts, news feeds, documents, audio, and web articles with Google Gemini API, Groq failover, aiogram 3.x, and SQLite.

---

## Commercial Services

* **Custom Telegram Bot Ecosystems**  
  Architecting high-load bots using aiogram 3.x, resilient webhook dispatchers, multi-step FSM intake flows, role-based access control (RBAC), and interactive inline management dashboards.

* **Workflow Automation & Third-Party Integrations**  
  Synchronizing bots with external platforms, Google Sheets API v4, CRM systems, payment gateways, and custom REST APIs with guaranteed idempotency and error recovery.

* **AI & LLM Integration**  
  Deploying multi-model LLM pipelines using Google Gemini and Groq, prompt orchestration, cross-lingual translation, automated content synthesis, and semantic lead scoring.

* **Data Scraping & Ingestion Infrastructure**  
  Building high-throughput non-blocking parsers (aiohttp, BeautifulSoup4, feedparser) equipped with anti-SSRF protection, content hashing deduplication, and automated reporting (CSV/Excel).

* **Architectural Audits & Optimization**  
  Refactoring existing Python applications to resolve event-loop blocking, implementing SQLite WAL tuning, configuring thread pools for heavy I/O, and containerizing systems with Docker Compose.

---

## Engineering Standards

* **Defensive Programming**: Zero-trust data boundaries, strict type checking with mypy, Pydantic data schemas, circuit breakers, exponential backoff with jitter, and graceful degradation during external API outages.
* **Non-Blocking Asynchronous Runtime**: Strict avoidance of blocking calls inside the asyncio event loop. File I/O and synchronous library operations are isolated via thread pools (`asyncio.to_thread`).
* **High-Efficiency Persistence**: SQLite configured with Write-Ahead Logging (`PRAGMA journal_mode=WAL`), `PRAGMA synchronous=NORMAL`, and busy timeout handling, delivering high concurrent throughput with near-zero resource overhead.
* **Native Multilingual Architecture**: Comprehensive localization (English, Ukrainian, Russian) with clean decoupling between client-facing interfaces and administrative CRM controls.
* **Production Observability & Deployment**: Structured multi-level logging, robust error tracking, environment variable configuration (.env), and repeatable Docker Compose deployments.

---

## Contacts

* Telegram: [@Blacksamurai1312](https://t.me/Blacksamurai1312)
* Freelancehunt: [freelancehunt.com/freelancer/Blacksamurai1312.html](https://freelancehunt.com/freelancer/Blacksamurai1312.html)
* GitHub: [github.com/ecksecoder](https://github.com/ecksecoder)
