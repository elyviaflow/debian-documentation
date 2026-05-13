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
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-F39C12?style=flat-square)](CONTRIBUTING.md)

<br/>

*Built from real server implementations and testing environments.*  
*From fresh install to production-ready — all in one place.*

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
│   ├── installation/
│   │   ├── instalation.md
│   │   ├── ip-address-configuration.md
│   │   ├── repository-configuration.md
│   │   ├── openssh-server-configuration.md
│   │   ├── domain-name-server-configuration.md
│   │   └── isc-dhcp-server-configuration.md
│   ├── web-server/
│   │   ├── apache2-configuration.md
│   │   ├── nginx-configuration.md
│   │   ├── virtual-host-configuration.md
│   │   ├── routing-configuration.md
│   │   ├── ssl-https-configuration.md
│   │   └── firewall-configuration.md
│   ├── databases/
│   │   ├── mariadb-configuration.md
│   │   ├── phpmyadmin-configuration.md
│   │   ├── database-backup-configuration.md
│   │   └── database-restore-configuration.md
│   ├── application/
│   │   ├── php-configuration.md
│   │   ├── composer-configuration.md
│   │   ├── permissions-configuration.md
│   │   ├── laravel-configuration.md
│   │   └── codeigniter-configuration.md
│   ├── security/
│   │   ├── ufw-configuration.md
│   │   ├── fail2ban-configuration.md
│   │   └── ssh-hardening-configuration.md
│   ├── troubleshooting/
│   │   ├── nginx-error-fix.md
│   │   ├── apache2-error-fix.md
│   │   ├── mariadb-error-fix.md
│   │   ├── php-error-fix.md
│   │   └── network-error-fix.md
│   ├── CONTRIBUTING.md
│   └── README.md
├── CONTRIBUTING.md
└── README.md
```

---

## Getting Started

Recommended reading order for setting up a clean and stable Debian server environtment:

```
### 📦 Debian 11 Bullseye
- [Installation](./debian-11-bullseye/installation/installation.md)
- [Web Server](./debian-11-bullseye/web-server/)
- [Databases](./debian-11-bullseye/databases/)
- [Application](./debian-11-bullseye/application/)
- [Security](./debian-11-bullseye/security/)
- [Troubleshooting](./debian-11-bullseye/troubleshooting/)

### 📦 Debian 12 Bookworm
- [Installation](./debian-12-bookworm/installation/installation.md)
- [Web Server](./debian-12-bookworm/web-server/)
- [Databases](./debian-12-bookworm/databases/)
- [Application](./debian-12-bookworm/application/)
- [Security](./debian-12-bookworm/security/)
- [Troubleshooting](./debian-12-bookworm/troubleshooting/)

### 📦 Debian 13 Trixie
- [Installation](./debian-13-trixie/installation/installation.md)
- [Web Server](./debian-13-trixie/web-server/)
- [Databases](./debian-13-trixie/databases/)
- [Application](./debian-13-trixieapplication/)
- [Security](./debian-13-trixie/security/)
- [Troubleshooting](./debian-13-trixie/troubleshooting/)
```
> **📑 New To Debian?**
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

## Topics at a Glance

| # | Category | Description |
|:-:|----------|-------------|
| 01 | **System** | Installation, initial configuration, and performance tuning |
| 02 | **Networking** | Interface setup, DNS, and virtual host management |
| 03 | **Web Servers** | Nginx, Apache, and PHP configuration |
| 04 | **Databases** | MariaDB and MySQL setup and management |
| 05 | **Security** | SSH hardening, firewall rules, and system security |
| 06 | **Maintenance** | Monitoring, troubleshooting, and upkeep |

---

## Contributing

Contributions, corrections, and additions are welcome.

1. Fork this repository
2. Create a branch: <br>`git checkout -b fix/topic-name`
3. Commit your changes: <br>`git commit -m "fix: clarify nginx config step"`
4. Open a Pull Request

Please follow the existing document structure and formatting conventions. See [`CONTRIBUTING.md`](CONTRIBUTING.md) for details.

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
