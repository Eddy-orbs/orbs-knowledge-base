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
| QuickSwap | O | O | O |  | O |  | Polygon, Eth, Base, POLZK EVM |  |  |
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

## Quick Observations
- dLIMIT and dTWAP appear to be the broadest integration surface across partners.
- Liquidity Hub appears present in a smaller but still meaningful subset of projects.
- Perp Hub appears in a more selective set of integrations.
- Solver-related integrations appear concentrated in a distinct subset of aggregation / routing / infrastructure projects.
- Some entries include explicit chain scope, which should later be normalized into machine-readable lists.

## Follow-up Cleanup Tasks
- Normalize chain names and casing.
- Convert date formats into ISO-like format where possible.
- Separate confirmed official integrations from sheet-only entries if needed.
- Add a `source confidence` column later.

## Sources
- User-provided partner sheet snapshot (2026-04-21)
- https://www.orbs.com/ecosystem/
- Official integration announcements under https://www.orbs.com/
