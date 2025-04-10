# Smart Inventory Management System

A full-stack inventory and lifecycle management platform designed to support technical laboratories with reliable tracking, testing data logging, and quality control enforcement. This system was developed to meet the evolving needs of departmental MakerSpace labs, offering a scalable and maintainable approach to inventory monitoring and control.

## 🔍 Introduction

This project leverages the Laravel framework with Vue.js frontend components to deliver a feature-rich, database-driven solution for tracking laboratory equipment and components. Inspired by the demands of quality control and scientific environments, the system offers robust role-based access control, statistical data views, lifecycle traceability, and modular architecture for extending monitoring and test validation functionality.

Originally scaffolded using the Laravel Boilerplate, it integrates:
- Backend dashboard with CoreUI and Spatie/Permission for user management
- Frontend built on Bootstrap 4 with Laravel Livewire tables for searchable, sortable interfaces
- Built-in support for authentication, multilingual access, and data seeding for testing and simulation


---

## 👥 Demo Credentials

| Role     | Email               | Password       |
|----------|---------------------|----------------|
| Admin    | admin@example.com   | admin_user     |
| User     | user@example.com    | regular_user   |
| Lecturer | lecturer@example.com| lecturer_user  |

---

## 🎯 Key Features

- ✅ Inventory lifecycle tracking with update history and soft deletion
- 📊 Validation-ready database design for asset condition and calibration logs
- 🔒 Multi-role access (Admin, User, Lecturer) with scoped permissions
- 📦 Asset registration with category, location, and serial metadata
- 📈 Vue.js-powered analytics view for anomaly detection and usage trends
- 🧪 Testing data handling modules for QA scenarios and pre/post analysis
- 📤 Export-ready reports for maintenance, testing, and compliance audits

---

## 🛠 Technologies Used

- **Backend**: PHP, Laravel, MySQL
- **Frontend**: Vue.js, Bootstrap 4, Laravel Livewire
- **Tools**: Node.js, Composer, NPM, Artisan CLI
- **DevOps**: GitHub Actions, WAMP Server, Bash scripting

---

## 🚀 Getting Started

### Prerequisites
Ensure WAMP server (or equivalent) is installed and a database user is configured.

### 1. Install Dependencies

```bash
# PHP dependencies
composer install

# Optional: Resolve memory issues
php -d memory_limit=-1 /usr/local/bin/composer install

# Node modules
npm install
npm run dev
