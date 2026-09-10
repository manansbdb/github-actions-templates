<p align="center">
  <img src="docs/banner.svg" alt="GitHub Actions Templates banner" width="100%" />
</p>

<h1 align="center">github-actions-templates</h1>

<p align="center">
  <strong>EN</strong> Reusable CI workflows for Node.js and Python<br/>
  <strong>PT</strong> Workflows reutilizáveis de CI para Node.js e Python
</p>

<p align="center">
  <a href="https://github.com/manansbdb/github-actions-templates/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge" alt="GitHub Actions" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Ready-to-copy **GitHub Actions** workflows for Node and Python CI (install, lint, test). | Workflows **GitHub Actions** prontos a copiar para CI Node e Python (install, lint, test). |
| Drop YAML into `.github/workflows/` and tweak versions/scripts. | Coloca o YAML em `.github/workflows/` e ajusta versões/scripts. |

```mermaid
flowchart LR
  A["📥 Push / PR"] --> B["⚙️ ci-node.yml / ci-python.yml"]
  B --> C["🧪 Lint + Test"]
  C --> D["✅ Green CI"]
  style A fill:#2088FF,stroke:#0366d6,color:#fff
  style B fill:#6366f1,stroke:#4338ca,color:#fff
  style C fill:#f59e0b,stroke:#b45309,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/github-actions-templates.git
cd github-actions-templates
```

### 2) Copy workflows / Copia workflows

```bash
mkdir -p /path/to/your-project/.github/workflows
cp .github/workflows/ci-node.yml /path/to/your-project/.github/workflows/
cp .github/workflows/ci-python.yml /path/to/your-project/.github/workflows/
# edit Node/Python versions and npm/pip scripts as needed
```

### Requirements / Requisitos

- `git`
- GitHub repository with Actions enabled

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/github-actions-templates.git
mkdir -p .github/workflows
cp github-actions-templates/.github/workflows/ci-node.yml .github/workflows/
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `.github/workflows/ci-node.yml` | Node.js CI workflow |
| `.github/workflows/ci-python.yml` | Python CI workflow |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
github-actions-templates/
├── docs/banner.svg
├── .github/workflows/ci-node.yml
├── .github/workflows/ci-python.yml
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
