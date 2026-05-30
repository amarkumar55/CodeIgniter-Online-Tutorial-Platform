# 🎓 CodeIgniter Online Tutorial Platform
### PHP · CodeIgniter · MySQL · MVC · Subscription System · LAMP Stack

![PHP](https://img.shields.io/badge/PHP-CodeIgniter-777BB4?style=flat-square&logo=php)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=flat-square&logo=mysql)
![Bootstrap](https://img.shields.io/badge/Bootstrap-Responsive_UI-7952B3?style=flat-square&logo=bootstrap)
![Stack](https://img.shields.io/badge/Stack-LAMP-FFA500?style=flat-square&logo=linux)
![License](https://img.shields.io/badge/License-Educational-lightgrey?style=flat-square)

> A database-driven online education platform built on CodeIgniter — structured video tutorials, subject subscriptions, and an interactive comment/reply system, all on a clean MVC backend.

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────┐
│              USER LAYER                      │
│  Browse · Subscribe · Watch · Comment/Reply  │
└──────────────────┬──────────────────────────┘
                   │
┌──────────────────▼──────────────────────────┐
│         APPLICATION LAYER (MVC)              │
│                                              │
│  Controllers — request handling, auth        │
│  Models      — DB queries, business logic    │
│  Views       — HTML templates, Bootstrap UI  │
└──────────────────┬──────────────────────────┘
                   │
┌──────────────────▼──────────────────────────┐
│           INFRASTRUCTURE LAYER               │
│  MySQL — users, content, subscriptions       │
│  Apache — LAMP stack, URL routing            │
└─────────────────────────────────────────────┘
```

---

## ✨ Features

- 📹 Video tutorials organized by subject categories
- 👤 User registration and authentication
- ⭐ Subscription system — follow subjects or instructors
- 💬 Comment and reply system for interactive discussions
- 📚 Category-based content browsing
- 📱 Responsive UI — Bootstrap, desktop and mobile

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | CodeIgniter (PHP) |
| Architecture | MVC — clean controller/model/view separation |
| Database | MySQL |
| Frontend | HTML5 · CSS3 · Bootstrap · JavaScript · jQuery |
| Server | LAMP (Linux · Apache · MySQL · PHP) |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/amarskdev/CodeIgniter-Online-Tutorial-Platform.git
cd CodeIgniter-Online-Tutorial-Platform
```

### 1. Configure Database

Update `application/config/database.php`:

```php
$db['default'] = array(
    'hostname' => 'localhost',
    'username' => 'your_db_user',
    'password' => 'your_db_password',
    'database' => 'your_db_name',
);
```

### 2. Import Database Schema

```bash
mysql -u your_user -p your_db_name < database.sql
```

### 3. Set Base URL

Update `application/config/config.php`:

```php
$config['base_url'] = 'http://localhost/CodeIgniter-Online-Tutorial-Platform/';
```

### 4. Run via LAMP

Start Apache and MySQL, then open:

```
http://localhost/CodeIgniter-Online-Tutorial-Platform/
```

---

## 📁 Project Structure

```
application/
├── controllers/      # Auth, Tutorials, Subscriptions, Comments
├── models/           # User, Content, Subscription, Comment models
└── views/            # Blade-style PHP templates + Bootstrap layouts
system/               # CodeIgniter core framework
assets/
├── css/              # Custom stylesheets
├── js/               # jQuery + custom scripts
└── images/           # Static assets
```

---

## 🌍 Use Cases

- Online learning and video education portals
- Subscription-based content delivery systems
- Academic or skill-based training platforms
- CodeIgniter MVC reference implementation

---

## 🔭 Roadmap

- [ ] REST API layer for mobile client support
- [ ] Video upload and streaming (AWS S3)
- [ ] Payment gateway for premium subscriptions
- [ ] Docker + cloud deployment
- [ ] Search and filtering across tutorials

---

## 👤 Author

**Amar Kumar** — Senior Backend Engineer · IBM Certified AI Engineer  
📌 [LinkedIn](https://www.linkedin.com/in/amarskdev/) · 💻 [GitHub](https://github.com/amarskdev)

---

*MVC done right — clean separation of concerns, database-driven content, subscription workflows built from scratch.*
