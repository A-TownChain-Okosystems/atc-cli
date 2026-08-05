# atc-cli

CLI-Tool für A-TownChain-Ökosystem — wie `kubectl` für K8s.

## Commands (geplant)
- `atc status` — Kernel/Blockchain-Status
- `atc deploy <contract>` — Smart Contract deployen
- `atc call <addr> <method> <args>` — Contract aufrufen
- `atc query <table> <filter>` — Entity/Datenbank-Abfrage
- `atc peers` — P2P-Peers anzeigen
- `atc blocks` — Blockchain-Blocks anzeigen
- `atc tx <hash>` — Transaction-Details
- `atc did <id>` — DID-Lookup
- `atc kernel <info|stats|logs>` — Kernel-Diagnose

## Build
```bash
cargo build --release
```

## Status
- Initial: Repo erstellt 05.08.2026
- Sprache: Rust (std, CLI)

---
Copyright © Michael Wroblewski / A-TownChain-Okosystems. All Rights Reserved.
