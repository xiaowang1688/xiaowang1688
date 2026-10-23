# Xiaowang | Python Automation & QA Engineer

**API Testing · Playwright · Python Scripting · CI/CD · Data Workflows**

🌏 **Based in Mainland China (UTC+8) · Open to international remote positions and contract projects**

I develop **practical Python automation tools** for API testing, browser regression checks, business-data reconciliation, HTTP monitoring, and reliability diagnostics. My work is publicly reviewable: source code, offline tests, GitHub Actions CI, and engineering case studies.

I'm interested in **Python Automation Engineer, QA Automation Engineer, API Test Engineer, and automation scripting** roles. I work well with clear specifications, testable acceptance criteria, GitHub-based collaboration, and asynchronous documentation.

[![Python CI](https://github.com/xiaowang1688/python-automation-starter/actions/workflows/ci.yml/badge.svg)](https://github.com/xiaowang1688/python-automation-starter/actions/workflows/ci.yml)
[![Playwright Chromium E2E](https://github.com/xiaowang1688/python-automation-starter/actions/workflows/browser-e2e.yml/badge.svg)](https://github.com/xiaowang1688/python-automation-starter/actions/workflows/browser-e2e.yml)
[![Security Scanner CI](https://github.com/xiaowang1688/smart-contract-vulnerability-scanner/actions/workflows/ci.yml/badge.svg)](https://github.com/xiaowang1688/smart-contract-vulnerability-scanner/actions/workflows/ci.yml)

**[LinkedIn Profile](https://www.linkedin.com/in/%E6%B6%9B-%E5%BC%A0-30116924a/)** · **[Technical Résumé](https://github.com/xiaowang1688/python-automation-starter/blob/main/RESUME.md)** · **[Full Engineering Portfolio](https://github.com/xiaowang1688/python-automation-starter/blob/main/PORTFOLIO.md)** · **[QA Test Strategy & Evidence](https://github.com/xiaowang1688/python-automation-starter/blob/main/docs/QA_ENGINEERING_EVIDENCE.md)** · **[CI Results](https://github.com/xiaowang1688/python-automation-starter/actions)**

## Featured engineering work

### 1. [Python Automation & QA Portfolio](https://github.com/xiaowang1688/python-automation-starter)

A set of runnable, documented Python automation examples with automated regression tests.

| Project | What I implemented | Evidence |
| --- | --- | --- |
| [API health checks](https://github.com/xiaowang1688/python-automation-starter/blob/main/automation/healthcheck.py) | Configurable HTTP monitoring, expected statuses, timeouts, bounded retries, JSON reports; opt-in HTTPS bearer-token handling | [Tests](https://github.com/xiaowang1688/python-automation-starter/blob/main/tests/test_healthcheck.py) |
| [API regression suite](https://github.com/xiaowang1688/python-automation-starter/tree/main/projects/api-regression) | GET/POST checks, nested JSON assertions, JUnit XML and JSON outputs | [Tests](https://github.com/xiaowang1688/python-automation-starter/blob/main/tests/test_api_regression.py) |
| [Playwright browser tests](https://github.com/xiaowang1688/python-automation-starter/tree/main/projects/browser-e2e) | Real Chromium UI tests covering valid order submission and invalid inputs | [Browser workflow](https://github.com/xiaowang1688/python-automation-starter/actions/workflows/browser-e2e.yml) |
| [Order/settlement reconciliation](https://github.com/xiaowang1688/python-automation-starter/tree/main/projects/finance-reconciliation) | Validated CSV comparison with Decimal arithmetic and classified discrepancies | [Tests](https://github.com/xiaowang1688/python-automation-starter/blob/main/tests/test_reconcile.py) |
| [HTTP log triage](https://github.com/xiaowang1688/python-automation-starter/tree/main/projects/log-observability) | Service-level 5xx-rate and p95-latency detection using structured logs | [Tests](https://github.com/xiaowang1688/python-automation-starter/blob/main/tests/test_log_triage.py) |

**Validation:** Offline Python tests run on Python 3.10, 3.12 and 3.13. A separate GitHub Actions workflow runs the Playwright UI tests in actual headless Chromium and publishes screenshot evidence. Business-data fixtures and UI examples are synthetic, not customer records.

### 2. [Python Security Automation / Mythril Scanner](https://github.com/xiaowang1688/smart-contract-vulnerability-scanner)

A Python CLI wrapper for Solidity static-analysis automation with explicit subprocess execution, timeout handling, captured output, failure reporting, mocked unit tests, and GitHub Actions CI.

[Implementation](https://github.com/xiaowang1688/smart-contract-vulnerability-scanner/blob/main/contracts/scan_vulnerabilities.py) · [Tests](https://github.com/xiaowang1688/smart-contract-vulnerability-scanner/blob/main/tests/test_scanner.py) · [CI](https://github.com/xiaowang1688/smart-contract-vulnerability-scanner/actions/workflows/ci.yml)

*The scanner is an educational automation tool, not an audited security product.*

## Tools & engineering practices

**Python 3 · unittest · REST/HTTP API validation · Playwright/Chromium · JSON/CSV processing · GitHub Actions · Git · CLI scripting · subprocess automation · test reporting · structured logs**

I aim to deliver repeatable scripts with explicit failure handling, test coverage, safe configuration, and clear handover documentation.

## Remote collaboration / 国际远程合作

- **Location:** Mainland China, UTC+8
- **Preferred work:** Python automation, QA/test automation, API regression, browser testing, scripting and data workflows
- **Communication:** Chinese-first; I use translation assistance for English technical writing and async collaboration. Spoken English expectations can be discussed upfront.
- **How to evaluate my work:** Inspect the linked implementation and tests, review [CI history](https://github.com/xiaowang1688/python-automation-starter/actions), or share a practical coding assessment.
- **Contact:** [LinkedIn professional profile](https://www.linkedin.com/in/%E6%B6%9B-%E5%BC%A0-30116924a/) or, for non-sensitive initial technical inquiries, [open an issue in the portfolio repository](https://github.com/xiaowang1688/python-automation-starter/issues/new). Please do **not** include passwords, private data, or confidential documents in a public issue.

### 中文简介

我主要从事 **Python 自动化开发、接口测试、Playwright 浏览器自动化、CI/CD 与数据处理脚本**。目前公开项目包含可运行代码、单元测试、浏览器端到端测试以及 GitHub Actions 验证记录，可供招聘方直接核查。我长期居住中国大陆，希望参与国际团队的远程自动化开发或测试岗位，可借助翻译工具进行英文书面与异步协作。

> **Engineering portfolio:** Every featured project links to source code, test cases, documentation, and CI evidence. Sample business and browser data are synthetic; production suitability should be assessed for each engagement.
