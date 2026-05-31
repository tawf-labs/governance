# Tawf Foundation Governance

Governance repository for the Tawf Foundation. This repo defines the technical charter, governance model, teams, and access policies that guide the Tawf ecosystem.

The Tawf Foundation is the stewardship entity. Tawf Labs is the engineering organization that builds the protocols under the Foundation's governance.

## What Lives Here

| File | Purpose |
|------|---------|
| [CHARTER.md](CHARTER.md) | Technical charter covering mission, principles, and governance bodies |
| [GOVERNANCE.md](GOVERNANCE.md) | Two layer governance model via Community DAO and Sharia Council |
| [config.yaml](config.yaml) | GitHub org teams and repository access permissions |
| [CODEOWNERS](CODEOWNERS) | Pull request review assignment rules |
| [LICENSE](LICENSE) | Apache 2.0 |

## DAO Governance Layer

The on-chain governance contracts live in the [tawf-gov](https://github.com/tawf-labs/tawf-gov) repository, maintained by Tawf Labs. That repo contains the Solidity smart contracts implementing:

- **CommunityDAO** on chain proposal creation and voting weighted by reputation
- **ZKShariaDAO** private Sharia compliance verification with zero knowledge proofs
- **TawfDID** soulbound identity and reputation system
- **WakafTreasury** transparent endowment fund management

This `governance` repo documents the *model and process*. The `tawf-gov` repo implements the *protocol*.

## Entity Structure

| Entity | Role | GitHub |
|--------|------|--------|
| Tawf Foundation | Governance and stewardship | This repo |
| Tawf Labs | Engineering and protocol development | [github.com/tawf-labs](https://github.com/tawf-labs) |

## Quick Links

- [github.com/tawf-labs/governance](https://github.com/tawf-labs/governance)
- [github.com/tawf-labs](https://github.com/tawf-labs)
- [tawf.xyz](https://tawf.xyz)
- contact@tawf.labs
