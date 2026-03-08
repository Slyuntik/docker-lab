# Docker Lab: Веб-приложение с Flask + Nginx + PostgreSQL

## Описание проекта
Учебный проект по контейнеризации трехуровневого веб-приложения:
- **Frontend**: Nginx с статическим HTML + проксирование API
- **Backend**: Flask REST API для управления задачами
- **Database**: PostgreSQL для хранения данных

## Быстрый старт
```bash
# Клонировать репозиторий
git clone https://github.com/Slyuntik/docker-lab.git
cd docker-lab

# Создать .env файл из шаблона
cp .env.example .env

# Запустить приложение
docker compose up -d --build

# Открыть в браузере: http://localhost
