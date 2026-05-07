# Product Catalog – Inertia.js + Vue

A fictional product catalog built during my LIA internship.

This project is one of three separate implementations of the same application, created to compare different frontend approaches within the Laravel ecosystem.

## Purpose

The goal of this project was to explore and compare:

- Developer experience
- Component architecture
- State handling
- Routing and rendering patterns
- Overall workflow in Laravel applications

This version was built using Inertia.js with Vue to create a modern SPA-like experience while keeping Laravel as the backend.

## Tech Stack

- Laravel
- Inertia.js
- Vue
- Tailwind CSS
- SQLite

## Features

- Product listing
- Product detail pages
- Filtering and search
- SPA-like navigation
- Component-based UI

## Setup

```bash
composer install
npm install
cp .env.example .env
php artisan key:generate
touch database/database.sqlite
php artisan migrate --seed
npm run dev
php artisan serve
```

## Notes

This project was published with permission for portfolio purposes.

Part of a comparison project alongside:

- Laravel Livewire
- Inertia.js + React
