# GPT Auto Wave Trader — Site 03 Update Channel

This repository is the public update distribution channel for GPT Auto Wave Trader Site 03.

## Security status

Remote one-click updates remain fail-closed until a trusted signing root and locked dependency graph are established. Real-order submission remains disabled and manual confirmation remains required.

## Stable channel layout

The desktop app will read the stable update manifest from:

`updates/stable/manifest.json`

Each release must pass version, releaseCounter, SHA-256, Ed25519 signature, and anti-rollback checks before installation.

## Important

Never commit update-signing private keys, exchange API credentials, or other secrets to this repository.
