<div align="center">

# 🤖 Tokyo Bot

### Telegram-Based VPN Sales, Subscription & Panel Management Platform

**Tokyo Bot** is a powerful and extensible Telegram platform for managing **VPN sales, subscriptions, users, payments, panels, configurations, resellers, and automation** from a single ecosystem.

<p>
  <a href="https://github.com/DevZeRoIR/TokyoBot">
    <img src="https://img.shields.io/badge/GitHub-TokyoBot-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://t.me/tokyosvc">
    <img src="https://img.shields.io/badge/Telegram-Channel-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Channel"/>
  </a>
  <a href="https://t.me/tokyosvc">
    <img src="https://img.shields.io/badge/Telegram-Community-229ED9?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Community"/>
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/PHP-8.2%2B-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP"/>
  <img src="https://img.shields.io/badge/Ubuntu-22.04%20%7C%2024.04-E95420?style=flat-square&logo=ubuntu&logoColor=white" alt="Ubuntu"/>
  <img src="https://img.shields.io/badge/Apache-2.4-D22128?style=flat-square&logo=apache&logoColor=white" alt="Apache"/>
  <img src="https://img.shields.io/badge/MySQL-8.x-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/Telegram-Mini%20App-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram Mini App"/>
</p>

<p>
  <a href="https://github.com/DevZeRoIR/TokyoBot/stargazers">
    <img src="https://img.shields.io/github/stars/DevZeRoIR/TokyoBot?style=flat-square&color=f5c518" alt="Stars"/>
  </a>
  <a href="https://github.com/DevZeRoIR/TokyoBot/network/members">
    <img src="https://img.shields.io/github/forks/DevZeRoIR/TokyoBot?style=flat-square" alt="Forks"/>
  </a>
  <a href="https://github.com/DevZeRoIR/TokyoBot/issues">
    <img src="https://img.shields.io/github/issues/DevZeRoIR/TokyoBot?style=flat-square" alt="Issues"/>
  </a>
  <a href="https://github.com/DevZeRoIR/TokyoBot/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/DevZeRoIR/TokyoBot?style=flat-square" alt="License"/>
  </a>
</p>

</div>

---

## 📌 Table of Contents

* [✨ Overview](#-overview)
* [🚀 Why Tokyo](#-why-tokyo)
* [🧩 Supported Panels](#-supported-panels)
* [💳 Payment Methods](#-payment-methods)
* [⚙️ Features](#️-features)

  * [Sales & Subscriptions](#sales--subscriptions)
  * [User Experience](#user-experience)
  * [Reseller & Affiliate](#reseller--affiliate)
  * [Administration](#administration)
  * [Automation](#automation)
* [📱 Telegram Mini App](#-telegram-mini-app)
* [🏗️ Architecture](#️-architecture)
* [🔐 Security](#-security)
* [🚀 Installation](#-installation)
* [🧰 CLI Usage](#-cli-usage)
* [🔄 Update](#-update)
* [🗑️ Removal](#️-removal)
* [🔒 Webhook & SSL](#-webhook--ssl)
* [🗄️ Database & Backup](#️-database--backup)
* [🌍 Languages](#-languages)
* [🛠️ Configuration](#️-configuration)
* [🧪 Development](#-development)
* [🤝 Contributing](#-contributing)
* [🐞 Support & Issues](#-support--issues)
* [👥 Community](#-community)
* [📄 License](#-license)

---

# ✨ Overview

**Tokyo Bot** is an all-in-one Telegram platform created for businesses that sell VPN and network services.

It connects your **Telegram bot**, **Telegram Mini App**, **VPN management panels**, **payment systems**, **database**, and **administration tools** into one centralized environment.

Instead of manually handling orders, payments, configuration creation, renewals, traffic purchases, and customer management, Tokyo automates the complete workflow.

### The typical workflow

```text
                  ┌─────────────────────┐
                  │      CUSTOMER       │
                  └──────────┬──────────┘
                             │
                             ▼
                  ┌─────────────────────┐
                  │   Telegram Bot /    │
                  │    Mini App         │
                  └──────────┬──────────┘
                             │
               ┌─────────────┼─────────────┐
               │             │             │
               ▼             ▼             ▼
        ┌────────────┐ ┌────────────┐ ┌────────────┐
        │  Products  │ │  Payments  │ │  Wallet    │
        └─────┬──────┘ └─────┬──────┘ └─────┬──────┘
              │              │              │
              └──────────────┼──────────────┘
                             ▼
                  ┌─────────────────────┐
                  │     Tokyo Core      │
                  └──────────┬──────────┘
                             │
             ┌───────────────┼────────────────┐
             │               │                │
             ▼               ▼                ▼
      ┌────────────┐  ┌────────────┐   ┌────────────┐
      │ VPN Panels │  │  Database  │   │ Admin      │
      │ / APIs     │  │   MySQL    │   │ Dashboard  │
      └────────────┘  └────────────┘   └────────────┘
```

Tokyo is designed to handle the complete lifecycle:

**Browse → Purchase → Pay → Create Config → Deliver → Manage → Renew**

---

# 🚀 Why Tokyo?

### ⚡ Automation First

Tokyo is designed to remove repetitive manual operations from VPN businesses.

Automate:

* Product sales
* Payment processing
* Configuration creation
* Service delivery
* Renewals
* Traffic purchases
* Expiry notifications
* Customer notifications
* Database backups
* Reseller operations

### 📱 Telegram Native

Customers can interact with the entire system directly inside Telegram.

No separate customer portal is required for the main workflow.

### 🧩 Multi-Panel

Tokyo supports multiple VPN and networking panels from a single management platform.

### 💳 Multi-Payment

Use multiple payment methods in the same installation, including manual payment, cryptocurrency, local gateways, offline payments, and Telegram Stars.

### 👑 Reseller Ready

Tokyo includes tools for managing agents, resellers, referrals, cashback, balances, products, and customers.

---

# 🧩 Supported Panels

Tokyo supports a broad range of VPN, networking, and subscription management panels.

## VPN & Subscription Panels

| Panel                               |    Status   |
| ----------------------------------- | :---------: |
| 🟢 **Marzneshin**                   | ✅ Supported |
| 🟢 **Marzban**                      | ✅ Supported |
| 🟢 **Pasarguard**                   | ✅ Supported |
| 🟢 **Tokyo Panel / Tokyo Reseller** | ✅ Supported |
| 🟢 **3x-UI / Sanaei**               | ✅ Supported |
| 🟢 **Alireza**                      | ✅ Supported |
| 🟢 **Hiddify**                      | ✅ Supported |
| 🟢 **S-UI**                         | ✅ Supported |
| 🟢 **WGDashboard**                  | ✅ Supported |
| 🟢 **IBSng**                        | ✅ Supported |
| 🟢 **MikroTik**                     | ✅ Supported |
| 🟢 **Rebecca**                      | ✅ Supported |

### Supported ecosystem

Tokyo is designed to work with different deployment models and panel architectures, allowing the same customer-management and sales layer to operate across different infrastructure.

> Panel capabilities may vary depending on the API and features exposed by the connected panel.

---

# 💳 Payment Methods

Tokyo supports multiple payment workflows so you can choose the payment model that best fits your business.

## 💵 Manual & Offline

| Method                            | Type                                  |
| --------------------------------- | ------------------------------------- |
| 💳 **Card to Card**               | Manual payment / receipt verification |
| 🧾 **Offline Currency**           | Offline payment                       |
| 🧾 **Regional / Offline Payment** | Custom offline settlement             |

## 🪙 Cryptocurrency

| Method             | Type           |
| ------------------ | -------------- |
| 🪙 **Plisio**      | Cryptocurrency |
| 🪙 **NOWPayments** | Cryptocurrency |

## 🇮🇷 Iranian / Rial Gateways

| Method               | Type                    |
| -------------------- | ----------------------- |
| 💰 **ارزی ریالی ۳**  | Rial / local payment    |
| 💰 **ارزی ریال ۲**   | Rial / local payment    |
| 💰 **ارزی ریال ۱**   | Rial / local payment    |
| 🇮🇷 **آقای پرداخت** | Iranian payment gateway |
| 🇮🇷 **زرین‌پال**    | Iranian payment gateway |

## ⭐ Telegram Payments

| Method               | Type                    |
| -------------------- | ----------------------- |
| ⭐ **Telegram Stars** | Telegram-native payment |

> Payment availability can depend on gateway configuration, credentials, region, and provider-side requirements.

---

# ⚙️ Features

## 🛒 Sales & Subscriptions

* ✅ Automated VPN subscription sales
* ✅ Product management
* ✅ Service management
* ✅ Automated configuration creation
* ✅ Trial / test accounts
* ✅ Subscription renewal
* ✅ Additional traffic / volume purchase
* ✅ Subscription link retrieval
* ✅ Configuration retrieval
* ✅ QR code generation
* ✅ Protocol-aware configuration handling
* ✅ Product-specific pricing
* ✅ Service expiry management
* ✅ Customer purchase history

---

## 👤 User Experience

* ✅ Telegram Bot interface
* ✅ Telegram Mini App
* ✅ Wallet / balance system
* ✅ Service dashboard
* ✅ Purchase history
* ✅ Active service management
* ✅ Service renewal
* ✅ Additional volume purchase
* ✅ Configuration retrieval
* ✅ Subscription link updates
* ✅ Support section
* ✅ FAQ
* ✅ Custom tutorials
* ✅ Phone number verification
* ✅ Mandatory channel membership
* ✅ Customer notifications
* ✅ Service expiry reminders

---

## 💰 Reseller & Affiliate

Tokyo includes tools for operating a reseller ecosystem.

* ✅ Agent / reseller management
* ✅ Affiliate / referral system
* ✅ Referral rewards
* ✅ Cashback
* ✅ Reseller balances
* ✅ Reseller products
* ✅ Discount codes
* ✅ Gift codes
* ✅ Promotional tools
* ✅ Customer acquisition tracking
* ✅ Multi-level sales workflows

---

## 🛠️ Administration

### Web Admin Panel

Tokyo provides a dedicated web administration interface for managing the platform.

Features include:

* ✅ Dashboard
* ✅ User management
* ✅ Balance management
* ✅ Product management
* ✅ Service management
* ✅ Panel management
* ✅ Payment gateway management
* ✅ Admin management
* ✅ Message/text management
* ✅ Bot configuration
* ✅ Username generation settings
* ✅ Customer support management
* ✅ Reports and activity information
* ✅ Backup management
* ✅ Expiry management

---

## 🤖 Automation

Tokyo is built around background automation.

* ✅ Automatic service creation
* ✅ Automatic payment workflows
* ✅ Automatic configuration delivery
* ✅ Automatic expiry notifications
* ✅ Automatic reminders
* ✅ Automated backups
* ✅ Cron-based background jobs
* ✅ Webhook processing
* ✅ Resumable installer
* ✅ Automatic environment setup
* ✅ Automatic SSL provisioning

---

# 📱 Telegram Mini App

Tokyo includes a modern **Telegram Mini App** experience for customers.

The Mini App can be used for:

```text
┌─────────────────────────────┐
│       TOKYO MINI APP        │
├─────────────────────────────┤
│                             │
│  🛒 Products                │
│  📦 My Services             │
│  💳 Wallet                  │
│  🧾 Orders                  │
│  🔄 Renew                   │
│  📈 Add Traffic             │
│  ⚙️ Configuration           │
│  🎁 Discounts               │
│  👥 Referral                │
│  🎧 Support                 │
│                             │
└─────────────────────────────┘
```

The Mini App provides a cleaner in-Telegram experience for users who prefer managing their services without navigating external dashboards.

---

# 🏗️ Architecture

Tokyo can be viewed as several connected layers:

```text
                         TELEGRAM
                    ┌────────────────┐
                    │ Bot + Mini App │
                    └───────┬────────┘
                            │
                            ▼
                    ┌────────────────┐
                    │  TOKYO CORE    │
                    │ Business Logic │
                    └───────┬────────┘
                            │
        ┌───────────────────┼────────────────────┐
        │                   │                    │
        ▼                   ▼                    ▼
 ┌──────────────┐   ┌──────────────┐    ┌──────────────┐
 │ VPN Panels   │   │   Payments   │    │   Database   │
 │ APIs         │   │   Gateways   │    │    MySQL     │
 └──────────────┘   └──────────────┘    └──────────────┘
        │                   │                    │
        └───────────────────┼────────────────────┘
                            ▼
                    ┌────────────────┐
                    │  Admin Panel   │
                    └────────────────┘
```

This architecture allows the platform to separate:

* Customer interaction
* Business logic
* Payment processing
* Panel communication
* Persistent data
* Administration

---

# 🔐 Security

Tokyo is designed with several security-oriented mechanisms.

### HTTPS

Telegram webhook traffic is handled through HTTPS.

### Webhook Secret

Webhook requests can be protected using a secret token.

### Database Credentials

Database credentials are generated and stored during installation.

### Protected Administration

The web administration dashboard requires authentication.

### SSL Management

The installer integrates Let's Encrypt / Certbot for certificate provisioning and management.

### Installation Safety

The installer includes:

* Environment checks
* OS detection
* Dependency checks
* Network validation
* Resumable installation state
* Package recovery
* Configuration validation
* Apache configuration testing

---

# 🚀 Installation

## Requirements

| Requirement   | Recommended               |
| ------------- | ------------------------- |
| 🖥️ OS        | Ubuntu 22.04 / 24.04      |
| 🧠 RAM        | 1 GB+                     |
| 💾 Disk       | 2 GB+ free                |
| 🌐 Domain     | Required                  |
| 🗄️ Database  | MySQL                     |
| 🌐 Web Server | Apache                    |
| 🐘 PHP        | 8.2+                      |
| 🔒 SSL        | Let's Encrypt             |
| 📡 Network    | Publicly reachable server |

### Domain

Your domain must point to the server's public IP address.

Example:

```text
bot.example.com → SERVER_IP
```

### Recommended Server

For the cleanest deployment, start with a fresh Ubuntu server without:

* Apache
* Nginx
* MySQL / MariaDB
* phpMyAdmin
* Other VPN management panels

---

# ⚡ One-Line Installation

Run as `root`:

```bash
curl -fsSL https://raw.githubusercontent.com/DevZeRoIR/TokyoBot/main/install.sh -o install.sh && bash install.sh
```

The installer will automatically prepare the environment and guide you through the setup.

---

# 🎛️ Interactive Installer

After launching the installer, you can manage Tokyo from the interactive menu.

```text
╭────────────────────────────────────────────────╮
│ TOKYO — VPN Subscription Management             │
╰────────────────────────────────────────────────╯

[1]  Install Tokyo
[2]  Update Tokyo
[3]  Remove Tokyo
[4]  Migrate
[5]  Renew SSL certificate
[6]  Backup Database
[7]  Import Database
[8]  Help & Parameters
[9]  Exit
```

---

# 🧰 CLI Usage

Tokyo can also be managed directly from the command line.

## Commands

| Command         | Description                       |
| --------------- | --------------------------------- |
| `tokyo install` | Install Tokyo                     |
| `tokyo update`  | Update Tokyo                      |
| `tokyo remove`  | Remove Tokyo                      |
| `tokyo migrate` | Run migration                     |
| `tokyo renew`   | Renew SSL certificate             |
| `tokyo backup`  | Create database backup            |
| `tokyo import`  | Import database backup            |
| `tokyo menu`    | Open interactive management panel |

---

## Install Options

| Parameter      | Description                  |
| -------------- | ---------------------------- |
| `--token`      | Telegram bot token           |
| `--admin`      | Telegram admin chat ID       |
| `--domain`     | Bot domain                   |
| `--db-user`    | Database username            |
| `--db-pass`    | Database password            |
| `--version`    | Specific release version     |
| `--channel`    | `beta`, `release`, or `auto` |
| `-h`, `--help` | Show help                    |

---

## Examples

### Standard Installation

```bash
tokyo install
```

### Latest Stable Release

```bash
tokyo install --channel release
```

### Beta / Development

```bash
tokyo install --channel beta
```

### Specific Version

```bash
tokyo install --version 1.0.0
```

### Automated Installation

```bash
tokyo install \
  --token 123456789:ABCDEF \
  --admin 123456789 \
  --domain bot.example.com \
  --db-user tokyo \
  --db-pass StrongPassword123
```

---

# 🔄 Update

Update Tokyo using:

```bash
tokyo update
```

Or choose a specific channel:

```bash
tokyo update --channel release
```

```bash
tokyo update --channel beta
```

Or install a specific release:

```bash
tokyo update --version 1.0.0
```

The update workflow is designed to preserve the active configuration while deploying the new application files.

---

# 🗑️ Removal

To remove Tokyo:

```bash
tokyo remove
```

The removal process can clean:

* Tokyo application files
* Database environment
* Apache configuration
* phpMyAdmin
* Installed Tokyo state
* Related service configuration

> Always create a backup before removing a production installation.

---

# 🔒 Webhook & SSL

Tokyo uses an HTTPS Telegram webhook.

Example:

```text
https://bot.example.com:88/index.php
```

The installer can automatically:

1. Validate the domain
2. Verify DNS resolution
3. Request an SSL certificate
4. Configure Apache
5. Configure the HTTPS VirtualHost
6. Register the Telegram webhook
7. Verify webhook connectivity

### Webhook architecture

```text
Telegram
   │
   │ HTTPS
   ▼
https://bot.example.com:88/index.php
   │
   ▼
Apache
   │
   ▼
Tokyo Bot
```

---

# 🗄️ Database & Backup

Tokyo uses MySQL for persistent application data.

Database-related operations include:

* User data
* Products
* Services
* Orders
* Wallet information
* Payment records
* Referral data
* Panel information
* Bot settings

## Backup

Create a backup using:

```bash
tokyo backup
```

The backup process creates an SQL dump that can be stored locally and optionally delivered through Telegram.

## Import

To restore a database:

```bash
tokyo import
```

> Always verify the backup before performing a production restore.

---

# ⏱️ Cron & Background Tasks

Tokyo uses cron-based tasks for recurring operations.

Typical automated tasks may include:

* Expiry processing
* Reminder notifications
* Subscription maintenance
* Scheduled operations
* Background service tasks
* Automated notifications

The installer automatically checks and configures cron during deployment.

---

# 🧪 Development

The project supports a development-oriented workflow for testing new changes before stable releases.

### Development Branch

```bash
tokyo install --channel beta
```

### Stable Releases

For production deployments:

```bash
tokyo install --channel release
```

---

# 📁 Project Structure

A typical Tokyo installation looks similar to:

```text
tokyoprobotconfig/
│
├── config.php
├── index.php
├── table.php
├── composer.json
├── composer.lock
├── vendor/
│
├── panel/
│   ├── user.php
│   ├── users.php
│   ├── service.php
│   ├── product.php
│   ├── payment.php
│   ├── settings.php
│   └── ...
│
└── ...
```

The internal structure may change between releases as new modules are introduced.

---

# 🛠️ Configuration

Tokyo stores deployment-specific settings separately from the application logic.

Typical configuration includes:

```text
Telegram Bot Token
Admin Chat ID
Domain
Database Host
Database Name
Database Username
Database Password
Bot Username
Webhook Secret
```

Sensitive configuration values should never be committed to a public repository.

### Important

Do **not** upload:

```text
.env
config.php
database backups
bot tokens
private keys
SSL private keys
server credentials
```

to a public repository.

---

# 📊 Supported Business Features

Tokyo can be used for different business models, including:

### 🛍️ Direct Sales

Sell VPN services directly to end users.

### 👑 Reseller Model

Create reseller accounts and manage their balances and products.

### 🤝 Affiliate Model

Reward users for referring new customers.

### 🎁 Promotional Model

Use:

* Discount codes
* Gift codes
* Cashback
* Referral rewards
* Trial services
* Campaign-based offers

---

# 🌐 Languages

Tokyo supports multilingual environments.

Current language support includes:

* 🇬🇧 English
* 🇮🇷 Persian — فارسی
* 🇷🇺 Russian — Русский
* 🇨🇳 Chinese — 中文

---

# 🤝 Contributing

Contributions are welcome.

Before submitting a pull request:

1. Keep the change focused.
2. Test the feature locally.
3. Avoid committing secrets or credentials.
4. Follow the existing project structure.
5. Explain the reason for the change.
6. Include reproduction steps for bug fixes.

### Pull Request Flow

```text
Fork
  ↓
Create Branch
  ↓
Make Changes
  ↓
Test
  ↓
Commit
  ↓
Pull Request
  ↓
Review
  ↓
Merge
```

---

# 🐞 Bug Reports

Found a problem?

Open an issue:

👉 https://github.com/DevZeRoIR/TokyoBot/issues

When reporting a bug, include:

* Operating system
* PHP version
* Tokyo version
* Panel type
* Payment method
* Error message
* Relevant logs
* Steps to reproduce

**Never post your Telegram bot token, passwords, API keys, or private credentials.**

---

# 💬 Community & Support

### Telegram

<p>
  <a href="https://t.me/tokyosvc">
    <img src="https://img.shields.io/badge/Telegram-Channel-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Channel"/>
  </a>
  <a href="https://t.me/tokyosvc">
    <img src="https://img.shields.io/badge/Telegram-Community-229ED9?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Community"/>
  </a>
</p>

### GitHub

* ⭐ Star the repository
* 🐞 Report bugs
* 💡 Suggest features
* 🔧 Submit pull requests

---

# 📄 License

This project is distributed under the license included in the repository.

See:

👉 [`LICENSE`](./LICENSE)

---

<div align="center">

# 🤖 Tokyo Bot

### Sell. Automate. Manage. Scale.

A complete Telegram-based platform for VPN sales and service management.

<br>

**Built with ❤️ for the VPN management community**

<br>

<a href="https://github.com/DevZeRoIR/TokyoBot">
  ⭐ Star Tokyo Bot on GitHub
</a>

  •  

<a href="https://t.me/tokyosvc">
  💬 Join Telegram
</a>

</div>
