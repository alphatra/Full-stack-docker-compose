# Next.js + FastAPI + MySQL + phpMyAdmin Starter

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/alphatra/Full-stack-docker-compose) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Ten projekt to kompleksowy zestaw narzędzi do szybkiego rozpoczęcia projektu z wykorzystaniem Next.js, FastAPI, MySQL i phpMyAdmin, wszystko skonfigurowane w Dockerze!

## Funkcje

- **Next.js**: Modern framework for frontend.
- **FastAPI**: Szybki, nowoczesny framework do budowy API z Pythona 3.7+.
- **MySQL**: Niezawodny i sprawdzony system zarządzania bazami danych.
- **phpMyAdmin**: Narzędzie do zarządzania bazą danych przez interfejs WWW.
- **Docker**: Łatwe zarządzanie zależnościami i środowiskiem.

## Wymagania

- [Docker](https://www.docker.com/)
- [Docker-Compose](https://docs.docker.com/compose/)

## Jak zacząć

1. Sklonuj to repozytorium na swój lokalny komputer:

```bash
git clone https://github.com/alpphatra/next.js-fastapi-mysql-phpmyadmin.git
cd next.js-fastapi-mysql-phpmyadmin
```
2. Zbuduj i uruchom kontenery

```bash
docker-compose up --build
```
3. Otwórz swoją przeglądarkę i przejdź do:
- Frontend: http://localhost:3000
- Backend API: http://localhost:8000
- phpMyAdmin: http://localhost:8090
