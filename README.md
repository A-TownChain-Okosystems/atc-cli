# ATC-CLI — Command Line Interface

CLI-Tool für A-TownChain OS — Chain-Management, Wallet, Contracts, Node-Verwaltung.

## Befehle
```
atc chain status          — Chain-Status anzeigen
atc chain start           — Node starten
atc chain stop            — Node stoppen
atc chain sync            — Mit Netzwerk synchronisieren
atc wallet create         — Neues Wallet erstellen
atc wallet balance [addr] — Saldo anzeigen
atc wallet send <to> <amt> — Tokens senden
atc wallet history        — Transaktions-Historie
atc contract deploy <file> — Smart Contract deployen
atc contract call <addr> <fn> [args] — Contract-Funktion aufrufen
atc contract query <addr> <fn> [args] — Contract-Funktion lesen
atc node peers            — Verbundene Peers
atc node version          — Version anzeigen
atc block get <hash|num>  — Block abrufen
atc tx get <hash>         — Transaktion abrufen
atc net info              — Netzwerk-Info
atc config get|set <key> [val] — Konfiguration
```

## Usage
```bash
# Chain-Status
atc chain status
# Chain: A-TownChain Testnet (Chain-ID: 9000)
# Block: 12345  Peers: 8  TPS: 42

# Wallet
atc wallet create
# Address: ATCf9327118a7dfb30f72ba6aa82e1186078c42232884
# WARNING: Save your private key securely!
```

## Verwandte Repos
- [atc-wallet](https://github.com/A-TownChain-Okosystems/atc-wallet) — Wallet
- [atc-blockchain](https://github.com/A-TownChain-Okosystems/atc-blockchain) — Blockchain Core

[agent: aurora-base44-superagent-6a2756186106d6f0fbb105b5]
