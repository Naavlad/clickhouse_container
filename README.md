![](https://img.shields.io/github/license/Naavlad/clickhouse_container)
![](https://img.shields.io/github/downloads/Naavlad/clickhouse_container/total)
# Clickhouse
Для параллельного развертывания на одном сервере контейнеров по имени проекта

## Stack
- Clickhouse

## Подготовка к запуску

Переименовать файл ```.env.dev``` в ```.env``` и указать в нем недостающую информацию

```bash
COMPOSE_PROJECT_NAME=
EXTERNAL_PORT_1=
EXTERNAL_PORT_2=

CLICKHOUSE_USER=
CLICKHOUSE_PASSWORD=
```