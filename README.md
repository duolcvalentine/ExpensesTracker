# ExpenseTracker Pro

Professional expense tracking and financial management system built with Laravel 12, PHP 8.3, MySQL, Bootstrap 5, Laravel Breeze authentication support, Chart.js, DataTables, SweetAlert2, and Font Awesome.

## Default Admin

- Email: `admin@gmail.com`
- Password: `admin123`

## Core Features

- Registration, login, forgot/reset password, email verification, remember me, logout, profile, and change password
- Admin and User roles with route middleware
- Admin dashboard with users, income, expenses, net balance, monthly stats, recent transactions, category stats, reports, activity logs, settings, and backups
- User dashboard with income, expenses, transactions, monthly summaries, reports, budget tracking, and profile settings
- CRUD for income, expenses, categories, budgets, users, and transactions
- Receipt image upload with validation and public storage
- Chart.js analytics for monthly income vs expenses, category pie charts, budget usage, cash flow, and yearly-style trend views
- Search and filters by text, dates, category, type, and amount
- CSV, PDF, and XLSX report exports
- CSRF protection, validation requests, password hashing, Eloquent ORM, role middleware, and policies
- Seeders for 50 users, 10 categories, 500 transactions, and 20 budgets

## Quick Start

See [docs/INSTALLATION.md](docs/INSTALLATION.md).

## Documentation

- [Database Schema](docs/DATABASE_SCHEMA.md)
- [Folder Structure](docs/FOLDER_STRUCTURE.md)
- [API and Route Documentation](docs/API_DOCUMENTATION.md)
