<div align="center">

<br/>

<p align="center">
  <img src="https://assets.celestiahub.web.id/img/elyvianame.png" width="500">
</p>


**Debian Server Administration — Practical Reference**

<br/>

[![Debian 11](https://img.shields.io/badge/Debian-12-A81D33?style=flat-square&logo=debian)](#)
[![License](https://img.shields.io/badge/License-MIT-4A90D9?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-2ECC71?style=flat-square)]()
[![Documentation](https://img.shields.io/badge/Documentation-Stable-27AE60?style=flat-square)](#)
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
debian-11-bullseye/
│   
├── 01-installation/
│   ├── instalation.md
│   ├── ip-address-configuration.md
│   ├── repository-configuration.md
│   ├── openssh-server-configuration.md
│   ├── domain-name-server-configuration.md
│   └── isc-dhcp-server-configuration.md
├── 02-web-server/
│   ├── apache2-configuration.md
│   ├── nginx-configuration.md
│   ├── virtual-host-configuration.md
│   ├── routing-configuration.md
│   ├── ssl-https-configuration.md
│   └── firewall-configuration.md
├── 03-database/
│   ├── mariadb-configuration.md
│   ├── phpmyadmin-configuration.md
│   ├── database-backup-configuration.md
│   └── database-restore-configuration.md
├── 04-application/
│   ├── php-configuration.md
│   ├── composer-configuration.md
│   ├── permissions-configuration.md
│   ├── laravel-configuration.md
│   └── codeigniter-configuration.md
├── 05-security/
│   ├── ufw-configuration.md
│   ├── fail2ban-configuration.md
│   └── ssh-hardening-configuration.md
├── 06-troubleshooting/
│   ├── nginx-error-fix.md
│   ├── apache2-error-fix.md
│   ├── mariadb-error-fix.md
│   ├── php-error-fix.md
│   └── network-error-fix.md
└── README.md
```

---

## Getting Started

This guide helps you set up a Debian server environment inside VirtualBox for learning and testing purposes.

### 📌 1. Requirements
Before installation, make sure you have the following:

**💻 Host System Requirements**
Make sure your computer supports virtualization:
- CPU with virtualization support (Intel VT-x / AMD-V)
- At least 8GB RAM (4GB minimum if only running VM)
- At least 30GB free storage

**🧰 Required Software**
- [`Virtual Box`](https://virtualbox.org/) — Virtual machine software
- [`Virtual Box`](https://virtualbox.org/wiki/Downloads) — Optional (USB, RDP, extra features)

### 📥 2. Download Debian ISO (Official)
Always use official sources:
- [`Debian Official Website`](https://www.debian.org/) — Main project page.
- [`Debian ISO Downloads`](https://www.debian.org/CD/http-ftp/) — Main project page.

### 📦 3. Choose Debian Version
**🧱 Debian 12 (Bullseye)**
Recommended for modern server environments.
| Official Page | Direct Download |
|---------------|-----------------|
|[`Bookworm`](https://www.debian.org/releases/bookworm/)|[`Download ISO`](https://cdimage.debian.org/cdimage/archive/12.0.0/amd64/iso-dvd/debian-12.0.0-amd64-DVD-1.iso)|

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

For more information, see [CONTRIBUTING.md](../CONTRIBUTING.md).

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
