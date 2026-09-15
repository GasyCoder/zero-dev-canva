# Zero Dev Canva

This is a project combining Laravel with modern frontend tooling.

## Overview

A development canvas powered by Laravel, Vite, and TypeScript.

## Getting Started

### Prerequisites
- PHP 8.1+
- Node.js 18+
- Composer
- pnpm

### Installation

```bash
# Install PHP dependencies
composer install

# Install Node dependencies
pnpm install

# Copy environment file
cp .env.example .env

# Generate application key
php artisan key:generate

# Run migrations
php artisan migrate

# Start development server
pnpm dev
