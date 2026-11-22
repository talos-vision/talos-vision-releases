# Talos Vision releases

Installers and signed release manifests for [Talos Vision](https://talos-vision.com).

Talos Vision is a free desktop app (Windows / macOS / Linux) that works as an MCP server for Claude Code and Codex.
Your AI can use databases, SSH, remote desktop, a browser, APIs, Redis, MongoDB, Git, Kubernetes, S3, documents and more
through plugins — while user names and passwords stay in an encrypted vault on your machine; the AI never sees them,
and risky actions wait for your approval.

- Download: https://talos-vision.com/en/download/
- Guide: https://talos-vision.com/en/guide/ · Plugins: https://talos-vision.com/en/plugins/
- ภาษาไทย: https://talos-vision.com/th/

## Verifying a release

Every release has `SHA256SUMS` and `releases.json`, each signed with an offline Ed25519 key (`*.sig`; the key id there is the first 16 hex characters below).
SHA-256 of the public keys (SPKI DER) — also published at https://talos-vision.com/en/security/:

- current: `1aee2aae0786c6e0d93635223a24ee44b0540b30e4a751ec674ca8147bf86c3f`
- spare: `211bdc4bc6d167bc2b7c3c90eab4a67df567121bae2b809ca1756d7ccdc88993`
