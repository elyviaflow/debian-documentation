# Contributing to ElyviaFlow Debian Docs

Thank you for taking the time to contribute. This document outlines the process and conventions for submitting contributions to this repository.

---

## Table of Contents

```
CONTRIBUTING.md
│
├── Code of Conduct
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

By participating in this project, you agree to maintain a respectful and constructive environment. Criticism of content is welcome — criticism of people is not.

---

## How to Contribute

### Reporting Issues

If you find an error, outdated command, or unclear explanation:

1. Open an [Issue](../../issues/new)
2. Use a clear, descriptive title
3. Include the affected file path (e.g., `05-security/ssh-remote-access.md`)
4. Describe what is wrong and, if possible, what the correct information should be

> **Note:** Please check existing issues before opening a new one to avoid duplicates.

---

### Suggesting New Topics

To suggest a topic that isn't currently covered:

1. Open an [Issue](../../issues/new) with the label `enhancement`
2. Describe the topic and why it would be useful
3. Mention which Debian versions it applies to

If you plan to write the guide yourself, mention that in the issue so it can be assigned to you.

---

### Submitting a Pull Request

```
1. Fork this repository
      │
      ├── 2. Clone your fork locally
      │         git clone https://github.com/your-username/repo-name.git
      │
      ├── 3. Create a new branch
      │         git checkout -b fix/ssh-keygen-step
      │         git checkout -b docs/add-ufw-guide
      │
      ├── 4. Make your changes
      │         Follow the document conventions below
      │
      ├── 5. Commit your changes
      │         git commit -m "docs: add UFW basic configuration guide"
      │
      ├── 6. Push to your fork
      │         git push origin your-branch-name
      │
      └── 7. Open a Pull Request
                Describe what changed and why
```

---

## Document Conventions

### File & Folder Naming

| Rule | Example |
|------|---------|
| Lowercase only | ✅ `ssh-remote-access.md` |
| Words separated by hyphens | ✅ `initial-setup.md` |
| No spaces or underscores | ❌ `SSH Remote Access.md`, `ssh_setup.md` |
| Place files in the correct category folder | ✅ `05-security/firewall-configuration.md` |

Folder structure reference:

```
01-system/
02-networking/
03-web-servers/
    ├── nginx/
    └── apache/
04-databases/
05-security/
06-maintenance/
```

---

### Markdown Formatting

Every document should follow this structure:

```markdown
# Title of the Guide

Brief one or two sentence description of what this guide covers.

---

## Prerequisites

- Debian 11 / 12 / 13
- Root or sudo access
- Any other requirements

---

## Section Title

Explanation text here.

```bash
# Commands go in fenced code blocks with language tags
apt update && apt upgrade -y
```

> **Note:** Use blockquotes for tips, warnings, or important callouts.

---

## Next Steps

- Link to related guide
- Link to related guide
```

**Additional formatting rules:**

- Use `##` for main sections, `###` for subsections — never skip heading levels
- All code blocks must specify a language tag: ` ```bash `, ` ```nginx `, ` ```sql `, etc.
- File paths should use inline code: `edit /etc/nginx/nginx.conf`
- Commands that require root should include a comment: `# run as root` or use `sudo`

---

### Writing Style

| Guideline | Detail |
|-----------|--------|
| **Voice** | Direct and instructional. Write "Run this command" not "You should run this command" |
| **Tense** | Present tense throughout |
| **Audience** | Assume basic Linux familiarity, not advanced sysadmin knowledge |
| **Language** | English only for consistency |
| **Brevity** | Explain the *what* and *why*, not just the *how* — but keep it concise |
| **Testing** | Only document commands you have personally tested |

---

## Commit Message Guidelines

Follow the [Conventional Commits](https://www.conventionalcommits.org/) format:

```
<type>: <short description>
```

| Type | When to use |
|:----:|-------------|
| `docs` | Adding or updating documentation content |
| `fix` | Correcting an error, broken command, or outdated info |
| `feat` | Adding a new guide or section |
| `refactor` | Restructuring or reformatting without content changes |
| `chore` | Repository maintenance (README, .gitignore, etc.) |

**Examples:**

```bash
docs: add MariaDB remote access configuration
fix: correct ufw rule syntax in firewall guide
feat: add Debian 13 Trixie installation section
refactor: restructure nginx folder into subpages
```

Keep the description under 72 characters. Use the PR body for longer explanations.

---

## Review Process

```
Pull Request Opened
      │
      ├── Automated checks (formatting, broken links)
      │
      ├── Content review
      │     ├── Accuracy — is the information correct?
      │     ├── Clarity — is it easy to follow?
      │     └── Conventions — does it match this guide?
      │
      ├── Changes requested (if needed)
      │     └── Author revises → re-review
      │
      └── Approved & Merged
```

Response time target: **within 7 days** for initial review.  
If your PR has not received a response after 7 days, feel free to leave a comment to follow up.

---

<div align="center">

<br/>

Thank you for helping make this documentation better.

**ElyviaFlow**

<br/>

</div>
