# Посчитай и сбереги · Count & Save

**Учёт личных финансов, который работает без интернета, понимает обычную речь
и банковские выписки и одинаково доступен с телефона, из браузера и в Telegram.
Сервер — у вас дома, без облаков.**

🌐 **Сайт проекта: <https://wallettransactions.github.io/>** · [English](https://wallettransactions.github.io/en/)

- 📱 **Android-приложение** — полноценный учёт на телефоне, работает офлайн и
  синхронизируется, когда появляется сеть.
- 🖥️ **Веб-кабинет** — аналитика, остатки по кошелькам, курсы валют, доступ
  для семьи.
- 💬 **Telegram-бот** — «Кофе 200», и трата записана.
- 🤖 **ИИ-помощник** — траты своими словами и импорт банковских выписок на
  локальной модели. ИИ только предлагает, записываете вы.
- 🔌 **MCP-сервер** — вопросы о ваших тратах из LM Studio, Claude и других
  ИИ-ассистентов, только чтение.
- 🏠 **Свой сервер дома** — база, отчёты и ИИ работают на вашем железе.
  [Как поставить](https://wallettransactions.github.io/self-hosting/)

## Репозитории

| Репозиторий | Что внутри |
|---|---|
| [WalletTransactions.github.io](https://github.com/WalletTransactions/WalletTransactions.github.io) | Сайт продукта (ru/en), MkDocs Material |
| [android-wallet](https://github.com/WalletTransactions/android-wallet) | Android-приложение: операции, кошельки, отчёты, курсы, синхронизация |
| [wallet-web](https://github.com/WalletTransactions/wallet-web) | Веб-кабинет (SPA) |
| [wallet-telegram](https://github.com/WalletTransactions/wallet-telegram) | Telegram-бот: отчёты и ввод трат |
| [wallet-api](https://github.com/WalletTransactions/wallet-api) | Леджер и протокол синхронизации |
| [wallet-report](https://github.com/WalletTransactions/wallet-report) | Отчёты, только чтение |
| [wallet-ai](https://github.com/WalletTransactions/wallet-ai) | Доступ к локальной LLM: разбор трат текстом, импорт выписок, чат о деньгах |
| [wallet-mcp](https://github.com/WalletTransactions/wallet-mcp) | MCP-сервер для ИИ-ассистентов, только чтение |
| [google-auth](https://github.com/WalletTransactions/google-auth) | Вход через Google, сессии и роли |
| [wallet-gateway](https://github.com/WalletTransactions/wallet-gateway) | Единая точка входа и маршрутизация |
| [wallet-docs](https://github.com/WalletTransactions/wallet-docs) 🚧 | Справка по системе на основе спецификаций |
| [wallet-common](https://github.com/WalletTransactions/wallet-common) | Общий C++-код сервисов |
| [wallet-infra](https://github.com/WalletTransactions/wallet-infra) | Развёртывание на `docker compose`, мониторинг, логи |

Серверная часть — C++17, PostgreSQL, Redis; клиент — Java/Android и JS.

---

**Count & Save** — personal finance that works offline, understands plain
language and bank statements, and runs on your own server at home.
Android app, web dashboard, Telegram bot, local AI assistant and an MCP server
for AI assistants. Learn more at **<https://wallettransactions.github.io/en/>**.
