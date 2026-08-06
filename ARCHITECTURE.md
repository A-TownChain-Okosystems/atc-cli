# 🌳 Architektur — atc-cli

> **Stand:** 2026-08-06 | **Version:** v1.0.0
> **Teil von:** [A-TownChain Ökosystem](https://github.com/A-TownChain-Okosystems)

## Beschreibung

CLI-Tool für A-TownChain OS. Status, Wallet, Mining, Send, Mint, Explore, Install.

## Metadaten

| Metrik | Wert |
|--------|------|
| Layer | L7 — Application |
| Sprint | 3.0 |
| ATC-Standards | ATC-24, ATC-86 |
| Status | 🟠 Aufbau |
| Code-Repo | [atc-cli](https://github.com/A-TownChain-Okosystems/atc-cli) |
| Wiki-Repo | [atc-cli-wiki](https://github.com/A-TownChain-Okosystems/atc-cli-wiki) |

## Komponenten-Übersicht

| Komponente | Beschreibung | Status |
|-----------|-------------|--------|
| `kai_cli.atc` | CLI-Main: command parsing, help, config, interactive mode | 📋 GEPLANT |
| `repl.atc` | Interactive REPL: eval, history, multi-line, tab completion | 📋 GEPLANT |
| `ecdsa_impl.atc` | ECDSA-Tool: keypair gen, sign, verify, tx building | 📋 GEPLANT |
| `bigquery_pipeline.atc` | BigQuery-Pipeline: GitHub metrics, blockchain stats, sync | 📋 GEPLANT |
| `atc_issues_summary.atc` | Issue-Tracker: sprint assignment, summary, critical detection | 📋 GEPLANT |
| `hf_review_pipeline.atc` | HuggingFace-PR-Review: severity, PR summary | 📋 GEPLANT |

## Architektur-Baum

```
atc-cli/
├── README.md
├── LICENSE
├── .gitignore
├── STATUS.md
├── ROADMAP.md
├── CHANGELOG.md
├── ARCHITECTURE.md
├── FILE_REGISTER.md
├── kai_cli.atc
├── repl.atc
├── ecdsa_impl.atc
├── bigquery_pipeline.atc
├── atc_issues_summary.atc
├── hf_review_pipeline.atc
```

## Abhängigkeiten

- **ATCLang Stdlib** (atc-stdlib)
- **ATC VM** (atc-vm)
- **ATC Kernel** (atc-kernel)

## Roadmap

| Phase | Aufgabe | Status |
|-------|---------|--------|
| Sprint 3.0 | Komponenten-Definition | ✅ ERLEDIGT |
| Sprint 3.0 | Architektur-Baum | ✅ ERLEDIGT |
| Sprint 3.0 | Stub-Dateien erstellen | 🔄 IN ARBEIT |
| Sprint 3.0 | Implementierung | 📋 GEPLANT |
| Sprint 3.0.1 | Tests | 📋 GEPLANT |
| Sprint 3.0.2 | Dokumentation | 📋 GEPLANT |

---
*Auto-generiert 2026-08-06 · Aurora (MasterBrain · Base44)*
