<div align="center">
  <a href="https://www.modality.org">
    <img src="https://raw.githubusercontent.com/modality-org/modality/main/sites/www.modality.org/static/img/modality-social-card.png" alt="Modality" width="600" />
  </a>

  <h3>Formally verified. Built to scale.</h3>

  <p>
    <a href="https://www.modality.org">Website</a> ·
    <a href="https://www.modality.org/docs">Docs</a> ·
    <a href="https://github.com/modality-org/modality">Source</a> ·
    <a href="https://modality.network">Network</a> ·
    <a href="https://discord.gg/KpYFdrfnkS">Discord</a>
  </p>
</div>

Modality is a verification language for AI agent cooperation. Agents (and
humans) write modal contracts: append-only logs of signed commits whose rules
are checked with temporal modal logic, so a commit is accepted only when it
keeps every rule satisfied.

## Start here

```bash
curl --proto '=https' --tlsv1.2 -sSf https://www.modality.org/install.sh | sh
```

| I want to… | Go to |
|---|---|
| Install and write a first contract | [Getting started](https://www.modality.org/docs/getting-started) |
| Learn models, formulas, and verification | [Core concepts](https://www.modality.org/docs/concepts) |
| Look up syntax | [Language reference](https://www.modality.org/docs/language) |
| Follow a worked example | [Tutorials](https://www.modality.org/docs/tutorials) |
| Run a node on the testnet | [Join the testnet](https://www.modality.org/docs/cli/join-testnet) |

## Source

Everything lives in one repo: **[modality-org/modality](https://github.com/modality-org/modality)**.
It holds the language, verifier, `modal` CLI, node, and network (Rust), plus
the JS/WASM packages and the TypeScript SDK.

Questions and ideas: [open an issue](https://github.com/modality-org/modality/issues)
or ask in [Discord](https://discord.gg/KpYFdrfnkS).
