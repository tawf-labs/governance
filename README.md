# Tawf Labs Governance

Organization-level governance repository for Tawf Labs. This repo defines teams, access policies, the technical charter, and the governance model that guides the Tawf ecosystem.

## What Lives Here

| File | Purpose |
|------|---------|
| [CHARTER.md](CHARTER.md) | Tawf Labs Technical Charter — mission, principles, governance bodies |
| [GOVERNANCE.md](GOVERNANCE.md) | Full two-layer governance model — Community DAO and Sharia Council |
| [config.yaml](config.yaml) | GitHub org teams and repository access permissions |
| [CODEOWNERS](CODEOWNERS) | Pull request review assignment rules |
| [LICENSE](LICENSE) | Apache 2.0 |

## DAO Governance Layer

The on-chain governance contracts live in the [tawf-gov](https://github.com/tawf-labs/tawf-gov) repository. That repo contains the Solidity smart contracts implementing:

- **CommunityDAO** — on-chain proposal creation and reputation-weighted voting
- **ZKShariaDAO** — private Sharia compliance verification with zero-knowledge proofs
- **TawfDID** — soulbound identity and reputation system
- **WakafTreasury** — transparent endowment fund management

This `governance` repo documents the *model and process*. The `tawf-gov` repo implements the *protocol*.

## Quick Links

- **Organization:** [github.com/tawf-labs](https://github.com/tawf-labs)
- **Website:** [tawf.xyz](https://tawf.xyz)
- **Contact:** contact@tawf.labs
