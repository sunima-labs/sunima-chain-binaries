# Sunima Chain Binaries

Binary release for the `sunima_8081-2` testnet — Regenesis v3 (Sep 4, 2026).

## Files

| Binary | SHA-256 |
|--------|---------|
| sunimad-linux-amd64 | 58bbc38a... |
| sunimad-darwin-arm64 | 58bbc38a... |
| genesis.json | 0e2cfd9c... |

All files signed with minisign key `B165A34E4BA4CE21`.

## Download

```bash
curl -LO https://github.com/sunima-labs/sunima-chain-binaries/releases/download/v14-regenesis/sunimad-linux-amd64
curl -LO https://github.com/sunima-labs/sunima-chain-binaries/releases/download/v14-regenesis/genesis.json
```

## Verify

```bash
sha256sum -c sunimad-linux-amd64.sha256
minisign -V -p sunima-minisign.pub -m sunimad-linux-amd64
```
