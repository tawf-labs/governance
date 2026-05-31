# Tawf Foundation Technical Charter

## 1. Mission

The Tawf Foundation stewards the open infrastructure layer for Islamic economic principles on-chain. We govern decentralized protocols that enable Muslims and faith aligned users to participate in Web3 without compromising their values. The protocols replace speculation with purpose, opacity with transparency, and exclusion with verified participation.

## 2. Core Principles

### 2.1 Risk Sharing (Mudarabah / Musharakah)

All Tawf financial instruments must embody genuine risk sharing between parties. No instrument may guarantee a fixed return independent of underlying asset performance.

### 2.2 Asset Backing

Every financial product must be backed by identifiable, verifiable real world assets or productive economic activity. Purely speculative instruments are prohibited.

### 2.3 Wealth Circulation (Zakat, Infaq, Sadaqah, Waqf)

The protocols must facilitate the circulation of wealth through obligatory and voluntary charitable mechanisms, preventing hoarding and enabling community investment.

### 2.4 Radical Transparency

All protocol operations, fund flows, and governance decisions must be publicly verifiable on-chain. Privacy is preserved for individuals via zero knowledge proofs. Institutional transparency is absolute.

### 2.5 Sharia Compliance by Design

Compliance is not an after market review. It is encoded into protocol parameters, contract logic, and governance processes from inception.

## 3. Governance Bodies

### 3.1 Community DAO

The primary decision making body. All DID verified community members may propose and vote on ecosystem matters. Voting is weighted by reputation, not by token holdings.

### 3.2 Sharia Council

An independent body of qualified Islamic scholars who hold Tawf DID credentials. The Council reviews all DAO decisions for Sharia compliance and holds veto authority. Council deliberations and votes are conducted with ZK privacy.

### 3.3 Core Maintainers

The technical stewards of the protocol. Maintainers are responsible for smart contract development, security, deployments, and emergency response. Maintainers are appointed by the founder and confirmed by the Community DAO.

## 4. Decision Making

### 4.1 Community Proposals

Any DID holder meeting the minimum reputation threshold may submit a proposal. Proposals follow the lifecycle defined in [GOVERNANCE.md](GOVERNANCE.md).

### 4.2 Sharia Review

All proposals with financial, governance, or ethical implications are subject to Sharia Council review. The Council may approve, request revision, or veto. A veto is final and binding.

### 4.3 Emergency Actions

The Sharia Council and Core Maintainers jointly hold emergency pause authority. This power is limited to circumstances of critical protocol vulnerability or active exploitation. Any emergency action must be followed by a public post mortem and community vote to ratify or reverse.

## 5. Membership and Participation

### 5.1 Identity (Tawf DID)

Participation in governance requires a Tawf DID, a soulbound NFT that establishes a verified on chain identity. DIDs are issued through a credential verification process and are non transferable.

### 5.2 Reputation

Reputation is earned through constructive participation: voting, proposal authorship, code contributions, community building, and verified real world impact. Reputation determines voting weight and proposal eligibility.

### 5.3 Code of Conduct

All participants are expected to engage with honesty (sidq), trustworthiness (amanah), and mutual respect. Harassment, fraud, bad faith proposals, and attempts to subvert governance are grounds for reputation penalties up to and including DID revocation.

## 6. Technical Governance

### 6.1 Smart Contracts

Governance contracts live in [tawf-labs/tawf-gov](https://github.com/tawf-labs/tawf-gov). All contract upgrades require a Community DAO vote and Sharia Council approval. Emergency fixes follow the emergency action procedure.

### 6.2 Multi Signature

Critical protocol operations such as deployment, upgrades, and treasury management require multi signature approval from Core Maintainers. The signature threshold is documented in the governance contracts.

### 6.3 Security

All smart contracts must undergo internal review before deployment. Formal verification, audit engagement, and bug bounty programs shall be established as the protocol matures.

## 7. Intellectual Property

All Tawf Foundation repositories are licensed under the Apache License, Version 2.0, unless otherwise noted. Contributions are accepted under the same license. The Tawf name and logo are trademarks of the Tawf Foundation and may not be used without permission.

## 8. Charter Amendments

This charter may be amended through the following process:

1. Amendment proposal submitted to Community DAO with full rationale
2. 14 day public review period
3. Community DAO vote requiring 67% supermajority
4. Sharia Council review and approval
5. Updated charter published to this repository

## 9. Ratification

This charter was ratified on 31 May 2026 by Muhammad Zidan Fatonie, Founder of the Tawf Foundation, and is effective immediately for all Tawf Foundation repositories and ecosystem participants.

---

*Bismillahirrahmanirrahim*
