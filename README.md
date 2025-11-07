Кинохостинг — пакет файлов (MVP → Прод)

Содержимое:
- server/ — backend skeleton (Express, S3 helpers, queue)
- worker/ — транскодинг worker (ffmpeg example)
- client/ — минимальный React MVP
- docker-compose.yml — локальный стек (Postgres, Redis)
- terraform/ — примерный AWS IaC (S3)
- LEGAL_LICENSE_AGREEMENT_RU.txt — шаблон лицензионного договора
- financials/ — 12-month cost estimates (CSV and XLSX)

Дальнейшие шаги:
1) Настроить .env, создать S3 bucket, настроить RDS и Redis.
2) Запустить `docker-compose up --build`.
3) Настроить Stripe, Google Ad Manager и домен.
