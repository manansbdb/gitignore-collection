<p align="center">
  <img src="docs/banner.svg" alt="gitignore Collection banner" width="100%" />
</p>

<h1 align="center">gitignore-collection</h1>

<p align="center">
  <strong>EN</strong> Curated .gitignore files for Node, Python, Go, and Rust<br/>
  <strong>PT</strong> Ficheiros .gitignore curados para Node, Python, Go e Rust
</p>

<p align="center">
  <a href="https://github.com/manansbdb/gitignore-collection/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/gitignore-f14e32?style=for-the-badge" alt="gitignore" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| A small collection of **language `.gitignore`** templates (Node, Python, Go, Rust). | Uma coleção pequena de templates **`.gitignore`** (Node, Python, Go, Rust). |
| Copy the matching file to your repo root as `.gitignore`. | Copia o ficheiro certo para a raiz do repo como `.gitignore`. |

```mermaid
flowchart LR
  A["🗂 Pick language"] --> B["📄 gitignore/*.gitignore"]
  B --> C["📋 Copy as .gitignore"]
  C --> D["✅ Clean git status"]
  style A fill:#f59e0b,stroke:#b45309,color:#fff
  style B fill:#f14e32,stroke:#b91c1c,color:#fff
  style C fill:#2563eb,stroke:#1d4ed8,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/gitignore-collection.git
cd gitignore-collection
```

### 2) Apply / Aplica

```bash
# example: Node
cp gitignore/Node.gitignore /path/to/your-project/.gitignore
# Python → gitignore/Python.gitignore
# Go     → gitignore/Go.gitignore
# Rust   → gitignore/Rust.gitignore
```

### Requirements / Requisitos

- `git`
- No runtime dependencies

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/gitignore-collection.git
cp gitignore-collection/gitignore/Node.gitignore ./.gitignore
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `gitignore/Node.gitignore` | Node.js ignores |
| `gitignore/Python.gitignore` | Python ignores |
| `gitignore/Go.gitignore` | Go ignores |
| `gitignore/Rust.gitignore` | Rust ignores |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
gitignore-collection/
├── docs/banner.svg
├── gitignore/Node.gitignore
├── gitignore/Python.gitignore
├── gitignore/Go.gitignore
├── gitignore/Rust.gitignore
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
