# Package Registry

This document serves as a central registry for packages and dependencies used across my projects.

---

## SSH-Toolkit

**Description:** A CLI toolkit for streamlining SSH connections and managing VM environments.

### Core Dependencies
- **paramiko** (Python) - SSH protocol implementation
- **cryptography** (Python) - Cryptographic recipes and primitives
- **PyYAML** (Python) - YAML parser for configuration files
- **click** (Python) - CLI framework for command-line interfaces

### Development Dependencies
- **pytest** - Testing framework
- **black** - Code formatter
- **flake8** - Linting tool

---

## Commonplace Book

**Description:** Digital commonplace book app for collecting, tagging, and searching notes, quotes, and ideas.

### Core Dependencies
- **Flask** (Python) - Web framework
- **SQLAlchemy** (Python) - Database ORM
- **Flask-SQLAlchemy** (Python) - Flask integration for SQLAlchemy
- **Whoosh** (Python) - Full-text search library
- **Flask-WTF** (Python) - Form handling
- **Jinja2** (Python) - Template engine

### Development Dependencies
- **pytest** - Testing framework
- **pytest-flask** - Flask testing utilities
- **black** - Code formatter
- **flake8** - Linting tool

---

## Python-Automator

**Description:** Automation scripts for Linux system maintenance, backup, and monitoring.

### Core Dependencies
- **psutil** (Python) - System and process utilities
- **schedule** (Python) - Job scheduling
- **requests** (Python) - HTTP library
- **python-crontab** (Python) - Cron job management

### Development Dependencies
- **pytest** - Testing framework
- **black** - Code formatter
- **pylint** - Code analysis tool

---

## CyberSec Playground

**Description:** Educational sandbox for practicing networking and cybersecurity concepts.

### Core Dependencies
- **scapy** (Python) - Packet manipulation program
- **netfilterqueue** (Python) - Network packet manipulation
- **pycryptodome** (Python) - Cryptographic modules (replaces deprecated pycrypto)
- **nmap** - Network scanner (system package)

### Development Dependencies
- **pytest** - Testing framework
- **black** - Code formatter
- **bandit** - Security linting tool

---

## Common Development Tools

These tools are used across multiple projects:

### Python
- **Python 3.8+** - Programming language runtime
- **pip** - Package installer
- **virtualenv** / **venv** - Virtual environment tools
- **poetry** - Dependency management (alternative)

### Version Control
- **Git** - Version control system
- **pre-commit** - Git hook framework

### Code Quality
- **black** - Code formatter
- **flake8** / **pylint** - Linting tools
- **mypy** - Static type checker
- **pytest** - Testing framework
- **coverage** - Code coverage measurement

### Containerization
- **Docker** - Container platform
- **docker-compose** - Multi-container orchestration

---

## Package Management Guidelines

### Installation
For Python projects, install dependencies using:
```bash
pip install -r requirements.txt
```

### Development Setup
1. Create a virtual environment
2. Install development dependencies
3. Run tests to verify setup

### Security
- Regularly update dependencies
- Use `pip-audit` or `safety` to check for vulnerabilities
- Pin versions in production

---

*Last Updated: December 2025*
