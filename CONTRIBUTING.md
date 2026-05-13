# Contributing to ElyviaFlow

Thank you for taking the time to contribute. This document explains the standards, workflow, and structure used in this repository.

---

## Table of Contents

```text
CONTRIBUTING.md
│
├── Code of Conduct
├── Repository Structure
├── How to Contribute
│   ├── Reporting Issues
│   ├── Suggesting New Topics
│   └── Submitting a Pull Request
│
├── Document Conventions
│   ├── File & Folder Naming
│   ├── Markdown Formatting
│   └── Writing Style
│
├── Commit Message Guidelines
└── Review Process
```

---

## Code of Conduct

By participating in this project, you agree to maintain a respectful and constructive environment.

### Respect other contributors

- Focus criticism on content, not people
- Keep discussions professional and technical
- Help maintain beginner-friendly documentation quality


---

## Repository Structure

This repository is organized by Debian version and category.

```
debian-documentation/
│
├── debian-version-codename/
│   ├── installation/
│   ├── web-server/
│   ├── databases/
│   ├── application/
│   ├── security/
│   ├── troubleshooting/
│   └── README.md
│
├── CONTRIBUTING.md
└── README.md
```
## Example Structure

```
debian-11-bullseye/
│
├── installation/
│   ├── installation.md
│   ├── ip-address-configuration.md
│   ├── repository-configuration.md
│   ├── openssh-server-configuration.md
│   ├── domain-name-server-configuration.md
│   └── isc-dhcp-server-configuration.md
│
├── web-server/
│   ├── apache2-configuration.md
│   ├── nginx-configuration.md
│   ├── virtual-host-configuration.md
│   ├── routing-configuration.md
│   ├── ssl-https-configuration.md
│   └── firewall-configuration.md
│
├── databases/
│   ├── mariadb-configuration.md
│   ├── phpmyadmin-configuration.md
│   ├── database-backup-configuration.md
│   └── database-restore-configuration.md
│
├── application/
│   ├── php-configuration.md
│   ├── composer-configuration.md
│   ├── permissions-configuration.md
│   ├── laravel-configuration.md
│   └── codeigniter-configuration.md
│
├── security/
│   ├── ufw-configuration.md
│   ├── fail2ban-configuration.md
│   └── ssh-hardening-configuration.md
│
├── troubleshooting/
│   ├── nginx-error-fix.md
│   ├── apache2-error-fix.md
│   ├── mariadb-error-fix.md
│   ├── php-error-fix.md
│   └── network-error-fix.md
│
└── README.md
```

---

## How to Contribute

### Reporting Issues

**If you find:**

- Incorrect commands
- Outdated configurations
- Broken formatting
- Missing explanations
- Typographical errors

## Please open an issue.
**Steps:**
```
1. Open an issue
2. Use a clear descriptive title
3. Mention the affected file path
4. Explain the problem clearly
5. Provide the corrected information if possible
```

**Example:**
```bash
debian-11-bullseye/web-server/nginx-configuration.md
```

> **Note:** Search existing issues before opening a new one to avoid duplicates.


---

## Suggesting New Topics

**To suggest a new documentation topic:**
```
1. Open an issue with the enhancement label
2. Explain the topic
3. Mention supported Debian versions
4. Explain why the topic is useful
```

**Examples:**

- Docker installation
- Redis configuration
- Node.js deployment
- Reverse proxy setup
- Monitoring tools

> If you want to write the guide yourself, mention it in the issue.


---

## Submitting a Pull Request

**1. Fork this repository**
```bash
gh repo fork elyviaflow/debian-documentation
```
**2. Clone your fork**
```bash
git clone https://github.com/elyviaflow/debian-documentation.git
```
**3. Create a new branch**
```bash
git checkout -b docs/add-nginx-guide
git checkout -b fix/mariadb-command-error
```
**4. Make your changes**
```bash
Follow repository conventions
```
**5. Commit changes**
```bash
git commit -m "docs: add nginx reverse proxy guide"
```
**6. Push branch**
```bash
git push origin your-branch-name
```
**7. Open a Pull Request**
```bash
Explain what changed and why
```
---

## Document Conventions

**File & Folder Naming**

| Rule | Example |
|----------|----------|
|Lowercase only|✅ nginx-configuration.md|
|Use hyphens|✅ ssl-https-configuration.md|
|No spaces|❌ Nginx Configuration.md|
|No underscores|❌ nginx_configuration.md|
|Use descriptive names|✅ database-backup-configuration.md|
|Place files in the correct category|✅ security/ufw-configuration.md|

---

## Category Placement Rules

|Category|Content Type|
|--------|------------|
|installation/|OS installation and basic setup|
|web-server/|Apache, Nginx, SSL, virtual hosts|
|databases/|MariaDB, MySQL, backups, restore|
|application/|PHP, Composer, Laravel, CodeIgniter|
|security/|Firewall, Fail2Ban, SSH hardening|
|troubleshooting/|Error fixes and debugging|

---

## Markdown Formatting

Every guide should follow this structure:
```
# Guide Title

Short explanation about what this guide covers.

---

## Prerequisites

- Debian 11 / 12 / 13
- Root or sudo access
- Internet connection

---

## Installation

**Explanation text here.**

```bash
# run as root
apt update && apt upgrade -y


> **Note:** Use blockquotes for important notes or warnings.

---

## Verification

Explain how to verify the configuration.

```bash
systemctl status nginx
```

---

## Next Steps

- Related guide link
- Related guide link

---
```
Additional Formatting Rules

Use `#` only once for the page title
Use `##` for main sections
Use `###` for subsections
Never skip heading levels
Always specify language tags for code blocks

**Use inline code formatting for:**
- Commands
- File paths
- Service names
- Configuration files

**Examples:**

systemctl restart nginx

/etc/nginx/nginx.conf

---

## Writing Style

|Guideline|Description|
|---------|-----------|
|Voice|Direct and instructional|
|Language|English only|
|Audience|Beginner-friendly|
|Tense|Present tense|
|Style|Clear and concise|
|Explanations|Explain what and why|
|Accuracy|Only document tested commands|

Preferred:

Install the package using the following command.

Avoid:

You should probably try installing the package.
```
---

## Commit Message Guidelines
Use the Conventional Commits format:
```<type>: <short description>```

**Allowed Types**

|Type|Usage|
|----|-----|
|docs|Documentation updates|
|fix|Error corrections|
|feat|New guide or feature|
|refactor|Structure or formatting improvements|
|chore|Repository maintenance|


**Examples**
docs: add phpmyadmin installation guide
fix: correct nginx server block syntax
feat: add Debian 13 installation documentation
refactor: reorganize troubleshooting section
chore: update repository README

**Rules:**

- Keep messages under 72 characters
- Use lowercase
- Be specific and concise

---

## Review Process
```
Pull Request Opened
      │
      ├── Structure validation
      │     ├── Correct folder placement
      │     ├── Correct file naming
      │     └── Markdown formatting
      │
      ├── Content review
      │     ├── Accuracy
      │     ├── Clarity
      │     ├── Readability
      │     └── Debian version compatibility
      │
      ├── Changes requested (if needed)
      │     └── Contributor updates PR
      │
      └── Approved & Merged
```
Target review response time:

Initial review: within 7 days

Follow-up review: within 3 days after updates


If there is no response after 7 days, feel free to leave a follow-up comment.


---

<div align="center"><br/>Thank you for contributing to ElyviaFlow Debian Docs.

<p align="center">
      <img src="https://assets.celestiahub.web.id/img/elyvianame.png" alt="ElyviaName PNG" width="500">
</p>

<br/></div>
