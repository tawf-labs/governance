# Tawf Governance Model

## Overview

The Tawf Foundation operates a two layer governance system designed to balance community decision making with principled Sharia oversight. The model is grounded in the Islamic principles of shura (consultative decision making) and hisbah (accountability and oversight).

## Layer 1: Community DAO

The Community DAO is the transparent, on chain governance layer. It handles day to day ecosystem decisions: protocol parameter changes, treasury allocations, feature prioritization, and ecosystem grants.

### Participation

- Voting requires a verified Tawf DID credential, a soulbound NFT
- Voting power is weighted by reputation, not by token holdings
- One identity, one vote, weighted by participation and contribution history
- No financial barrier to entry. No token purchase required.

### Proposal Lifecycle

1. **Submission.** Any DID holder meeting the reputation threshold may create a proposal.
2. **Review Period.** Proposals are open for community discussion and Sharia Council review.
3. **Voting Period.** Qualified DID holders cast votes: For, Against, or Abstain.
4. **Execution.** Approved proposals are queued and executed on chain.

### Default Parameters

| Parameter | Value |
|-----------|-------|
| Proposal Threshold | 100 reputation points |
| Voting Delay | 1 block |
| Voting Period | 50,400 blocks (~7 days) |
| Quorum | 1,000 votes |
| Council Veto Window | 3 days after vote close |

## Layer 2: Sharia Council

The Sharia Council is an independent oversight body composed of qualified Islamic scholars holding specialized Tawf DID credentials. The Council operates with zero knowledge privacy: scholar identities are protected while their credentials are verified on chain.

### Authority

- Veto power over any Community DAO decision found noncompliant with Sharia principles
- Advisory opinions on new protocol features and financial instruments
- Standards body for compliance criteria, aligned with AAOIFI
- Emergency pause capability for critical violations

### Privacy Model

Scholars prove their qualification via ZK proofs. A scholar demonstrates possession of valid credentials without revealing their identity or specific affiliations. Council votes are private. Only the aggregate outcome (pass or fail) is public.

### Compliance Standards

The Council evaluates proposals against:

- AAOIFI Sharia Standard No. 21 for Financial Screening
- Prohibition of riba (interest), gharar (excessive uncertainty), and maysir (gambling)
- Asset backing requirements for all financial instruments
- Risk sharing mandate, meaning no risk free return
- Ethical exclusion criteria covering alcohol, gambling, weapons, and similar sectors

## Decision Matrix

| Decision Type | Community DAO | Sharia Council | Binding |
|---------------|---------------|----------------|---------|
| Protocol parameters | Vote | Review window | Community vote with Council veto |
| Treasury allocation | Vote | Review window | Community vote with Council veto |
| Sharia compliance ruling | Advisory input | Final authority | Council binding |
| Emergency pause | None | Authorized | Council binding |
| Charter amendment | 67% supermajority | Must approve | Both required |

## Technical Implementation

The governance contracts are maintained in [tawf-labs/tawf-gov](https://github.com/tawf-labs/tawf-gov). Key contracts:

| Contract | Function |
|----------|----------|
| `CommunityDAO.sol` | Proposal creation, voting, execution |
| `ZKShariaDAO.sol` | Private Council voting with ZK proofs |
| `ProposalRegistry.sol` | Proposal batching and lifecycle |
| `TawfDID.sol` | Soulbound identity and reputation |
| `ProtocolAdmin.sol` | Emergency controls and admin |

## Roles

| Role | Description | Selection |
|------|-------------|-----------|
| **Maintainer** | Core protocol development and deploy authority | Appointed by founder, confirmed by DAO |
| **Council Member** | Sharia compliance oversight and veto authority | Nominated by peers, verified by credential |
| **Delegate** | Community representative and proposal champion | DID holders, weighted by reputation |
| **Contributor** | Code, docs, design, community | Open and merit based |

## Amendment Process

1. Proposal submitted to Community DAO with rationale and impact analysis
2. 14 day public review period
3. Community vote requiring 67% supermajority
4. Sharia Council review and approval
5. Charter and contract updates executed
