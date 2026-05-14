<div align="center">

<br/>

<p align="center">
  <img src="https://assets.celestiahub.web.id/img/elyvianame.png" width="500">
</p>


**Debian Server Administration — Practical Reference**

<br/>

[![Debian](https://img.shields.io/badge/Debian-11_%7C_12_%7C_13-A81D33?style=flat-square&logo=debian&logoColor=white)](https://www.debian.org/)
[![License](https://img.shields.io/badge/License-MIT-4A90D9?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-2ECC71?style=flat-square)]()
[![VirtualBox Ready](https://img.shields.io/badge/VirtualBox-Ready-183A61?style=flat-square&logo=virtualbox&logoColor=white)](#)
[![ElyviaFlow](https://img.shields.io/badge/ElyviaFlow-v1.0.0-6C5CE7?style=flat-square)](https://www.elyviaflow.com)

<br/>

*Comprehensive Debian server documentation for VirtualBox lab environments.*  
*Learn installation, configuration, security, and deployment step-by-step.*

<br/>

</div>

---

## Overview

This documentation was built from **real server implementations and testing environments**, designed to help both beginners and sysadmins navigate Debian server management with confidence. Clear, structured, and always practical.

---

## Repository Structure

```
debian-documentation/
│
├── debian-version-codename/
│   ├── 01-installation/
│   │   ├── instalation.md
│   │   ├── ip-address-configuration.md
│   │   ├── repository-configuration.md
│   │   ├── openssh-server-configuration.md
│   │   ├── domain-name-server-configuration.md
│   │   └── isc-dhcp-server-configuration.md
│   ├── 02-web-server/
│   │   ├── apache2-configuration.md
│   │   ├── nginx-configuration.md
│   │   ├── virtual-host-configuration.md
│   │   ├── routing-configuration.md
│   │   ├── ssl-https-configuration.md
│   │   └── firewall-configuration.md
│   ├── 03-database/
│   │   ├── mariadb-configuration.md
│   │   ├── phpmyadmin-configuration.md
│   │   ├── database-backup-configuration.md
│   │   └── database-restore-configuration.md
│   ├── 04-application/
│   │   ├── php-configuration.md
│   │   ├── composer-configuration.md
│   │   ├── permissions-configuration.md
│   │   ├── laravel-configuration.md
│   │   └── codeigniter-configuration.md
│   ├── 05-security/
│   │   ├── ufw-configuration.md
│   │   ├── fail2ban-configuration.md
│   │   └── ssh-hardening-configuration.md
│   ├── 06-troubleshooting/
│   │   ├── nginx-error-fix.md
│   │   ├── apache2-error-fix.md
│   │   ├── mariadb-error-fix.md
│   │   ├── php-error-fix.md
│   │   └── network-error-fix.md
│   └── README.md
│
├── CONTRIBUTING.md
└── README.md
```

---

## Getting Started

Recommended reading order for setting up a clean and stable Debian server environtment:

### 📦 Debian 11 Bullseye
- [Installation](./debian-11-bullseye/01-installation/installation.md)
- [Web Server](./debian-11-bullseye/02-web-server/)
- [Databases](./debian-11-bullseye/03-database/)
- [Application](./debian-11-bullseye/04-application/)
- [Security](./debian-11-bullseye/05-security/)
- [Troubleshooting](./debian-11-bullseye/06-troubleshooting/)

### 📦 Debian 12 Bookworm
- [Installation](./debian-12-bookworm/01-installation/installation.md)
- [Web Server](./debian-12-bookworm/02-web-server/)
- [Databases](./debian-12-bookworm/03-database/)
- [Application](./debian-12-bookworm/04-application/)
- [Security](./debian-12-bookworm/05-security/)
- [Troubleshooting](./debian-12-bookworm/06-troubleshooting/)

### 📦 Debian 13 Trixie
- [Installation](./debian-13-trixie/01-installation/installation.md)
- [Web Server](./debian-13-trixie/02-web-server/)
- [Databases](./debian-13-trixie/03-database/)
- [Application](./debian-13-trixie/04-application/)
- [Security](./debian-13-trixie/05-security/)
- [Troubleshooting](./debian-13-trixie/06-troubleshooting/)

> **📑 New To Debian?**<br>
> Start with the Installation section and continue in order for the best learning experience.

---

## Supported Versions

| Version | Codename | Released | Status |
|:-------:|:--------:|:--------:|:------:|
| Debian 11 | Bullseye | Aug 2021 | ✅ Supported |
| Debian 12 | Bookworm | Jun 2023 | ✅ Supported |
| Debian 13 | Trixie | 2025 | ✅ Supported |
| Latest | Rolling | — | 🔁 Upcoming |

---

## 📚 Topics at a Glance

| # | Category | Description |
|:-:|-----------|-------------|
| 01 | **Installation** | Debian installation, repositories, SSH, DNS, and DHCP configuration |
| 02 | **Web-Server** | Nginx, Apache, SSL, virtual hosts, routing, and firewall setup |
| 03 | **Database** | MariaDB, phpMyAdmin, backup, and restore management |
| 04 | **Application** | PHP, Composer, Laravel, CodeIgniter, and permissions setup |
| 05 | **Security** | UFW, Fail2Ban, SSH hardening, and server protection |
| 06 | **Troubleshooting** | Common fixes for web server, PHP, database, and network issues |

---

## 🤝 Contributing

Contributions, improvements, fixes, and new documentation are always welcome.

### How to Contribute

1. Fork this repository

2. Create a new branch:

```bash
git checkout -b fix/topic-name
```

3. Commit your changes:

```bash
git commit -m "fix: improve nginx configuration guide"
```

4. Push your branch and open a Pull Request

### Contribution Guidelines

- Follow the existing folder structure
- Keep documentation clear and beginner-friendly
- Use proper Markdown formatting
- Test commands before submitting documentation

For more information, see [CONTRIBUTING.md](./CONTRIBUTING.md).

---

## License

Distributed under the [MIT License](LICENSE).

---

<div align="center">

<br/>

Made with ❤️ by **ElyviaFlow**  
⭐ Star this repo if you find it helpful!
<br/>

</div>
