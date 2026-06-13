# Partners

## Summary
Based on the collected material so far, Orbs partners can be divided into three broad categories:
1. staking, ecosystem, and infrastructure-related partners
2. product-integration-oriented DeFi and DEX partners
3. major ecosystem infrastructure partnerships, including TON ecosystem infrastructure

## Working Categories
### Staking / Ecosystem Partners
- Celsius Network (historical example)
- Staking Rewards (ecosystem, staking discovery, and analytics context)

### Product / Protocol Integrations
- DEXs integrating dLIMIT and dTWAP
- Protocols integrating Liquidity Hub
- Derivatives-oriented integrations around Perpetual Hub
- Solver-related integrations across routing and aggregation infrastructure
- Ecosystem references around partners such as IVX and others in recent public posts

### Governance Platform / Ecosystem Use Cases
- TON.vote / TON community governance: TON.vote is an Orbs-developed TON governance platform. A 2026-06-03 Orbs Korea announcement states that the TON community's TON-to-GRAM ticker/name-change vote is taking place on TON.vote. Track this as a major ecosystem / partner use case comparable in prominence to QuickSwap partner-case notes, but categorize it as governance-platform usage rather than a DEX execution integration or a new Orbs product launch. Orbs Korea source: https://t.me/orbskrannouncement/524.

### Major Ecosystem Infrastructure Partnerships
- TON Ecosystem / The Open Network: treat as a major Orbs ecosystem partnership and infrastructure-provider case. Orbs is an independent Layer-3 infrastructure project that supports TON as a target ecosystem; it is not a TON Foundation subsidiary and should not be framed as a competing TON L1. Key Orbs contributions include TON Access decentralized RPC / network access infrastructure, TON.vote community governance infrastructure, TON Minter / Jetton issuance tooling, TON Verifier smart-contract verification tooling, and Single Nominator Smart Contract validator staking infrastructure.

## Current Structured Inventory
A more complete working table exists in `partner-inventory.md`, built from the user-provided sheet snapshot together with official-public references.

High-level pattern:
- dLIMIT and dTWAP integrations are the broadest and most repeated
- Liquidity Hub appears in a narrower set of projects
- Perpetual Hub is concentrated in fewer targeted partners
- Solver integrations form a separate partner cluster

## Notes
- The partner list should later be normalized into fields such as name, category, product, chain, status, and source
- If the Google Sheet can later be exported as CSV, this document should be regenerated from that structured source of truth

## QuickSwap Perpetual DEX Governance Approval Signal
As of late May / early June 2026, the QuickSwap Snapshot vote titled `Full Shift Of Decentralised Perpetuals to Orbs Network` closed with majority support for transitioning QuickSwap's decentralized perpetuals infrastructure to Orbs Network / Orbs Layer-3 Perpetual Hub.

Key points to preserve as a partnership / ecosystem-progress note:
- Status: Snapshot governance vote closed and passed / approved by voters; this should be described as governance approval, not as completed technical migration or production deployment unless later confirmed by an implementation notice.
- Snapshot result: approximately 4,447,678.6 Yes vs 987,318.6 No, for about 5,434,997.2 total voting power and roughly 81.8% Yes support.
- Proposed structure: QuickSwap would continue as the frontend brand and trading venue, while Orbs Layer-3 / Perpetual Hub would provide perpetual-contract execution and liquidity aggregation infrastructure wherever applicable.
- Reported economics: a 50:50 revenue split between QuickSwap and Orbs was mentioned in the media report.
- Context: QuickSwap and Orbs already have an established collaboration history around Liquidity Hub, zero-gas swaps, MEV protection, and advanced DEX execution infrastructure.
- Source confidence: Snapshot is the primary governance-result source. Orbs official X and CryptoBriefing are supporting/context sources.

## TON Ecosystem / The Open Network Partnership
Treat TON Ecosystem as a major partnership / ecosystem-infrastructure case for Orbs, comparable in importance to major partner-case notes such as QuickSwap but structurally different from DEX execution integrations.

Relationship summary:
- TON is the Layer-1 blockchain / ecosystem; Orbs is an independent Layer-3 infrastructure project that can support TON applications.
- Orbs should be described as an ecosystem partner and infrastructure provider for TON, not as a TON Foundation subsidiary and not as a competing TON L1.
- Orbs uses its Guardian-based decentralized network to provide infrastructure services that TON smart contracts or applications may not handle alone.
- Orbs supports both EVM-chain DeFi infrastructure and TON ecosystem infrastructure.
- Orbs was one of the early large investors in the TON project.
- Orbs contributes as a major TON ecosystem participant by operating TON nodes.
- Key TON cooperation project websites display `Powered by Orbs` or `Contributed by Orbs` style logo attribution in the footer.
- Tal Kol, Orbs co-founder and key development lead, is an official TON technical ambassador and has contributed to TON infrastructure / documentation together with Orbs developers.

Strategic importance:
- TON is closely connected with Telegram and therefore has a large global user base.
- Telegram Mini App growth can increase demand for on-chain services and network infrastructure.
- TON adoption is notable in emerging markets such as Asia, the Middle East, and CIS regions.

### TON Access
Source: https://www.orbs.com/ton-access/

- Category: decentralized RPC / Network Access Layer for TON.
- Purpose: reduce dependency on centralized RPC services, improve censorship resistance, strengthen resilience, and provide distributed network access.
- Orbs contribution: Guardian-based decentralized infrastructure, distributed RPC request handling, and improved network availability for TON users and applications.
- Partner-case framing: TON Access is a core TON ecosystem infrastructure service powered by the Orbs Guardian network.

### TON.vote / TON Community Governance Use Case
Source: https://www.orbs.com/ton-vote/

- Category: TON community governance voting system.
- Purpose: support community decision-making, transparency, and broader governance participation.
- Orbs contribution: voting infrastructure, decentralized verification-network usage, and governance-service operation support.
- 2026-06-03 use case: Orbs Korea announced that the TON community's TON-to-GRAM ticker/name-change vote is taking place on TON.vote. Source: https://t.me/orbskrannouncement/524.
- Caution: do not frame the TON-to-GRAM vote itself as an Orbs product update, Orbs rebrand, or new Orbs protocol feature.

### TON Minter
Operating URL: https://minter.ton.org/

- Category: TON Jetton issuance / token-creation tool.
- Former project name: Jetton.live.
- Summary: TON Minter is a TON blockchain Jetton issuance tool developed by Orbs. Jetton is TON's token standard, comparable to ERC-20 on Ethereum.
- Status notes: open-source project adopted as one of the official TON Community tools.
- Purpose: TON's early ecosystem lacked a standard easy tool for creating new Jettons. Orbs built Minter to automate token creation and help activate the TON token ecosystem.
- Key functions: users can input Token Name, Symbol, Decimals, and Initial Supply, then automatically deploy a Jetton Minter Contract and mint the initial supply.
- Metadata design: Orbs designed metadata to be stored on-chain to reduce risks such as token-name changes, symbol changes, or metadata loss.
- Ecosystem contribution: standardizes TON token issuance, supports new project launches, helps DEX liquidity ecosystem growth, and simplifies TON developer onboarding.
- Usage note: public materials indicate hundreds of Jettons have been created through TON Minter.

### TON Verifier
- Category: TON smart-contract verification service / developer tool.
- Summary: TON Verifier is a TON smart-contract verification service developed by Orbs, comparable in role to Etherscan Contract Verification on Ethereum.
- Purpose: TON's early ecosystem lacked standard tooling for checking deployed contract code, verifying source-code disclosure, and validating contract trustworthiness.
- Key functions: compares deployed TON contracts with source code to verify code identity and detect whether deployed code differs from the disclosed source.
- Trust and security contribution: helps users confirm whether a contract is verified, lets projects build trust through source-code disclosure, and supports contract transparency / malicious-contract detection.
- Ecosystem contribution: improves transparency, security, and developer confidence in the TON ecosystem.

### Single Nominator Smart Contract for TON Validators
- Category: TON validator staking / validator-fund security smart contract.
- Summary: Single Nominator Smart Contract is a validator-dedicated staking smart contract developed and open-sourced by Orbs for the TON ecosystem.
- Purpose: designed as a dedicated vault for a single validator to stake and manage TON more safely, protecting validator assets, strengthening operational security, reducing slashing / operational risk, and standardizing validator operations.
- Background: early TON validators often used general Wallet Contracts for validator operation, which could mix validator operating funds with personal funds and expose large validator stakes to hot-wallet or server-compromise risks.
- Structure: single-owner / single-nominator model. It is not a pool contract, not a delegation contract, and not intended for multi-user staking; it is a validator's personal dedicated contract.
- Validator separation model: assets remain in the Single Nominator Contract, while the validator server performs validation with limited authority. This is designed so that compromise of the validator server does not expose the full stake to arbitrary transfer or unlimited fund movement.
- Security features: limited command set for validator operations, such as stake, recover stake, and withdraw; cold-wallet-friendly design separating long-term fund custody from operational servers.
- Ecosystem impact: Single Nominator became one of the widely adopted / de facto standard models for TON validator operation, lowering validator entry barriers, improving operational security, enabling larger-scale staking participation, and supporting institution-grade validator operations.
- Orbs contribution: development, open-source release, and provision to the TON community.
- Answering note: treat this as recorded Orbs knowledge; do not describe it as unconfirmed or tentative.

### ORBS-TON Cooperation Significance
- TON was the first Non-EVM Layer-1 ecosystem that Orbs supported.
- Orbs' TON relationship should be framed as more than a simple partnership: Orbs directly built developer and infrastructure tooling for TON ecosystem growth.
- Main recorded cooperation cases: TON Access, TON.vote, TON Minter, TON Verifier, and Single Nominator Smart Contract for TON Validators.
- TON Foundation later selected Orbs as a sponsor for official hackathon activities, indicating expansion of the collaboration.

## Candidate Source Set
- https://www.orbs.com/orbs-partners-with-celsius-network/
- https://www.orbs.com/orbs-featured-on-staking-rewards/
- https://www.orbs.com/staking-rewards-features-orbs-pos-v3/
- https://www.orbs.com/BaseSwap-integrates-dLIMIT-dTWAP-powered-by-Orbs/
- https://www.orbs.com/Thena-integrates-dLIMIT-and-dTWAP-powered-by-Orbs/
- https://www.orbs.com/Omni-Exchange-integrates-dTWAP-and-dLIMIT-on-Base/
- https://www.orbs.com/Orbs-Perpetual-Hub-Integrates-with-IVX/
- Google Sheet provided by user (L3 current partners)
