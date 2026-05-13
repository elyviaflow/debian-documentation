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
├── debian-11-bullseye/
│   ├── installation.md
│   ├── initial-setup.md
│   └── performance-optimization.md
│
├── debian-12-bookworm/
│   ├── network-configuration.md
│   ├── dns-server.md
│   └── virtual-hosts.md
│
├── debian-13-trixie/
│   ├── nginx/
│   │   ├── installation.md
│   │   └── configuration.md
│   ├── apache/
│   │   ├── installation.md
│   │   └── configuration.md
│   └── php-configuration.md
│
├── 04-databases/
│   ├── mariadb.md
│   └── mysql.md
│
├── 05-security/
│   ├── ssh-remote-access.md
│   ├── firewall-configuration.md
│   └── security-hardening.md
│
├── 06-maintenance/
│   ├── troubleshooting.md
│   └── ...
│
├── CONTRIBUTING.md
└── README.md
```

---

## Getting Started

Recommended reading order for a clean Debian server setup:

```
1. System → Installation
         └── Initial Setup
               └── Performance Optimization

2. Security → SSH & Remote Access
            └── Firewall Configuration
                  └── Security Hardening

3. Networking → Network Configuration
              └── DNS Server
                    └── Virtual Hosts

4. Web Servers → Nginx or Apache
               └── PHP Configuration

5. Databases → MariaDB / MySQL

6. Maintenance → Troubleshooting
```

> **New to Debian?** Follow the order above top to bottom. Each section builds on the previous.

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
