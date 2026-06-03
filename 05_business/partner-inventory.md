# Partner Inventory (Structured Draft)

## Notes
- This file combines official-public integration references with the user-provided partner sheet snapshot.
- `O` is treated as active/present support.
- `X` is treated as removed / no longer active for that product line.
- Dates are preserved as provided and should be normalized later if needed.

## Column Meaning
- Liquidity Hub
- dLIMIT
- dTWAP
- dSLTP
- Perp Hub
- Solver
- Chain
- Date updated

## Structured Inventory

| Project | Liquidity Hub | dLIMIT | dTWAP | dSLTP | Perp Hub | Solver | Chain | Date updated | Notes |
|---|---|---|---|---|---|---|---|---|---|
| Algebra | O |  |  |  |  |  |  |  |  |
| QuickSwap | O | O | O |  | O |  | Polygon, Eth, Base, POLZK EVM | 2026-06 | Existing partner. QuickSwap Snapshot vote `Full Shift Of Decentralised Perpetuals to Orbs Network` closed with majority approval: approximately 4,447,678.6 Yes vs 987,318.6 No, about 81.8% Yes. Treat as governance approval / transition approval, not completed technical migration or production deployment until separately confirmed. |
| Thena | O | O | O | O | O |  | BNB |  |  |
| SpookySwap | O | O | O | O | O |  | Fantom, Sonic |  |  |
| SwapX | O | O | O |  |  |  |  |  |  |
| Chronos | O | O | O |  |  |  |  |  |  |
| IntentX | O |  |  |  | O |  | Base |  |  |
| Fenix | O |  |  |  |  |  |  |  |  |
| Lynex | O | O | O | O |  | O | Linea |  |  |
| PancakeSwap |  | X | O |  |  |  | BNB, Arbitrum, Linea, Base | 2025 - 3Q | dLIMIT removed |
| SushiSwap |  | O | O |  |  |  | Eth, Arb, Katana, ... |  |  |
| BaseSwap |  | O | O |  |  |  | Base |  |  |
| Pangolin |  | O | O |  |  |  | AVAX |  |  |
| Arbidex |  | O | O |  |  |  | Arbitrum |  |  |
| DragonSwap |  | O | O |  |  |  | Sei |  |  |
| Tea-Fi |  | O | O |  |  |  |  |  |  |
| SYMMIO |  |  |  |  | O |  |  |  |  |
| SpiritSwap |  |  | O |  |  |  | Sonic |  |  |
| Velora (ParaSwap) |  |  |  |  |  | O |  |  |  |
| ODOS |  |  |  |  |  | O |  |  |  |
| manifold |  |  |  |  |  | O |  |  |  |
| DODO |  |  |  |  |  | O |  |  |  |
| Rango Exchange |  |  |  |  |  | O |  |  |  |
| OpenOcean |  |  |  |  |  | O |  |  |  |
| KyberNetwork |  |  |  |  |  | O |  |  |  |
| Pear |  |  |  |  | O |  |  |  |  |
| Magpie |  |  |  |  |  | O |  |  |  |
| IVX |  |  |  |  |  | O | Berachain |  |  |
| XPanse |  |  |  |  |  | O |  |  |  |
| JST Digital |  |  |  |  |  | O |  |  |  |
| Privex |  |  |  |  | O |  |  |  |  |
| SparkDEX |  | O | O |  |  |  | Flare |  |  |
| Shadow |  | O | O |  |  |  | Sonic |  |  |
| OMNI Exchange |  | O | O |  |  |  | Base, Arbitrum | Oct 25 |  |
| Kodiak |  | O | O |  |  |  | Berachain | Oct 25 |  |
| Blackhole |  | O | O |  |  |  | Avalanche | Oct 25 |  |
| Atlantis |  |  |  |  | O |  | Monad | 2026 / 01 |  |
| TON Ecosystem / The Open Network |  |  |  |  |  |  | TON | 2026-06 | Major ecosystem infrastructure partnership / infrastructure-provider case. Orbs is an independent L3 infrastructure project supporting TON, not a TON Foundation subsidiary and not a competing TON L1. Key services include TON Access, TON.vote, TON Minter, TON Verifier, and Single Nominator Smart Contract. Orbs was an early large TON investor, operates TON nodes, and TON cooperation sites display Powered by Orbs / Contributed by Orbs attribution. |
| TON Access |  |  |  |  |  |  | TON | 2026-06 | Decentralized RPC / Network Access Layer for TON powered by Orbs Guardian-based infrastructure. Source: https://www.orbs.com/ton-access/ |
| TON.vote / TON community governance |  |  |  |  |  |  | TON | 2026-06 | Major governance-platform ecosystem use case. Orbs Korea reported that the TON community TON-to-GRAM ticker/name-change vote is taking place on TON.vote. Track like a major partner case, but categorize as governance-platform usage rather than a DEX execution product integration. Source: https://www.orbs.com/ton-vote/. |
| TON Minter |  |  |  |  |  |  | TON | 2026-06 | TON Jetton issuance tool developed by Orbs; former name Jetton.live; operating URL https://minter.ton.org/. Open-source and adopted as an official TON Community tool. Helps create Jettons without separate smart-contract development. |
| TON Verifier |  |  |  |  |  |  | TON | 2026-06 | TON smart-contract verification service developed by Orbs, comparable to Etherscan Contract Verification. Supports source-code/deployed-contract identity checks, transparency, security, and developer trust. Recorded Orbs knowledge. |
| Single Nominator Smart Contract |  |  |  |  |  |  | TON | 2026-06 | Orbs-developed and open-sourced validator-dedicated TON staking smart contract / vault. Single-owner model, not a pool or delegation contract. Designed to separate validator server operation from stake custody, limit operational command scope, reduce hot-wallet/server-compromise fund risk, and support standardized validator operations. Recorded Orbs knowledge. |

## Quick Observations
- dLIMIT and dTWAP appear to be the broadest integration surface across partners.
- Liquidity Hub appears present in a smaller but still meaningful subset of projects.
- Perp Hub appears in a more selective set of integrations.
- Solver-related integrations appear concentrated in a distinct subset of aggregation / routing / infrastructure projects.
- Some entries include explicit chain scope, which should later be normalized into machine-readable lists.
- QuickSwap's Snapshot vote for shifting decentralized perpetuals to Orbs Network closed with majority approval; continue watching for separate implementation / deployment confirmation.
- TON Ecosystem / The Open Network should be treated as a major Orbs ecosystem infrastructure partnership. TON Access, TON.vote, TON Minter, TON Verifier, and Single Nominator Smart Contract are the main structured use cases currently recorded.
- TON.vote should be treated as a major Orbs-developed governance-platform use case in the TON ecosystem; keep it separate from DEX / trading-product integration rows when answering.
- TON Access should be treated as decentralized RPC / network access infrastructure for TON, powered by the Orbs Guardian network.
- TON Minter should be treated as Orbs-developed Jetton issuance tooling for TON; TON Verifier should be treated as Orbs-developed TON smart-contract verification tooling.
- Single Nominator Smart Contract should be treated as Orbs-developed validator staking / fund-security infrastructure for TON validators, not as a public delegation pool.

## Follow-up Cleanup Tasks
- Normalize chain names and casing.
- Convert date formats into ISO-like format where possible.
- Separate confirmed official integrations from sheet-only entries if needed.
- Add a `source confidence` column later.

## Sources
- User-provided partner sheet snapshot (2026-04-21)
- https://www.orbs.com/ecosystem/
- Official integration announcements under https://www.orbs.com/
- QuickSwap Snapshot vote `Full Shift Of Decentralised Perpetuals to Orbs Network`: https://snapshot.box/#/s:quickvote.eth/proposal/0x2564e956ca2f1f9f0a814fe43b7ff0c5afece25dee7b0e6d91455751c2f85fc4
- QuickSwap / Orbs governance media report: https://cryptobriefing.com/quickswap-perpetuals-orbs-network-governance/
- Orbs official X QuickSwap-related post: https://x.com/orbs_network/status/2059085302195728762
- TON Access: https://www.orbs.com/ton-access/
- TON.vote: https://www.orbs.com/ton-vote/
- TON Minter: https://minter.ton.org/
- TON Verifier: recorded Orbs knowledge; teacher-group material dated 2026-06-03
- Single Nominator Smart Contract for TON Validators: recorded Orbs knowledge; teacher-group material dated 2026-06-03
- Orbs Korea announcement for TON.vote TON-to-GRAM vote use case: recorded Orbs knowledge; teacher-group material dated 2026-06-03
