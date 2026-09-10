<p align="center">
  <img src="docs/banner.svg" alt="github-actions-templates banner" width="100%" />
</p>

<h1 align="center">github-actions-templates</h1>

<p align="center">
  <strong>EN</strong> Reusable CI workflows for Node.js and Python projects.<br/>
  <strong>PT</strong> Workflows reutilizáveis de CI para projetos Node.js e Python.
</p>

<p align="center">
  <a href="https://github.com/manansbdb/github-actions-templates/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/type-templates-f59e0b?style=for-the-badge" alt="templates" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Reusable CI workflows for Node.js and Python projects. | Workflows reutilizáveis de CI para projetos Node.js e Python. |

```mermaid
flowchart LR
  A["📁 Template"] --> B["✏️ Adapt"]
  B --> C["📌 Commit"]
  style A fill:#f59e0b,stroke:#b45309,color:#fff
  style B fill:#3b82f6,stroke:#1d4ed8,color:#fff
  style C fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone

```bash
git clone https://github.com/manansbdb/github-actions-templates.git
cd github-actions-templates
```

### Use / Usar

```bash
# open the files in this repo and copy what you need into your project
ls
```

### Requirements / Requisitos

- `git`
- No paid services required / Sem serviços pagos

---

## What's included / O que inclui

| File | Description (EN) | Descrição (PT) |
|------|------------------|----------------|
| `.github/workflows/ci-node.yml` | Node.js CI (install, lint, test) | CI Node.js (install, lint, test) |
| `.github/workflows/ci-python.yml` | Python CI (pip, lint, pytest) | CI Python (pip, lint, pytest) |

## Usage / Uso

**EN:** Copy the workflow files into your repository under `.github/workflows/` and adjust versions, cache keys, and scripts as needed.

**PT:** Copia os ficheiros para `.github/workflows/` e ajusta versões, cache e scripts conforme o teu projeto.

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

**Network / Rede:** BTC (Bech32).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
