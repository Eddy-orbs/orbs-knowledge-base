# ORBS Token Overview

## Summary
ORBS is the core network token of the Orbs protocol. Based on the materials gathered so far, ORBS is tied to execution-related fee settlement, staking, Guardian selection, and PoS participant rewards. It should be understood not just as a trading asset, but as the center of the protocol’s incentive layer.

## Core Role
- Fee settlement related to application or infrastructure execution
- Staking asset
- Guardian election and network-security participation
- Reward distribution for PoS participants

## Supply Guidance
- Circulating supply and market figures are time-sensitive.
- Current circulating-supply questions should be answered with this user-facing wording: `현재 ORBS 유통량은 실시간으로 변동될 수 있어서, 최신 수치는 CoinGecko의 ORBS 페이지에서 확인하시면 됩니다: https://www.coingecko.com/en/coins/orbs`
- Live public market/supply references include CoinGecko, CoinMarketCap, and the Orbs supply API listed in the source inventory.
- The token role is best understood together with the whitepaper and PoS documentation.
- Token distribution details should be read together with `token-distribution-notes.md` and the official distribution paper.

## Cross-Chain Presence
ORBS has referenced token contract addresses across multiple networks and documented bridge routes. However, the canonical-token interpretation and chain-specific operating model should still be checked against official documents when precision matters.

## Sources
- https://coinmarketcap.com/currencies/orbs/
- https://www.coingecko.com/en/coins/orbs
- https://status.orbs.network/supply
- https://www.orbs.com/white-papers/orbs-token-distribution/

## Current Staking Reward Snapshot
User-provided snapshot as of 2026-04-29:

- Delegator reward rate: 6.67% annualized average.
- Guardian reward rate: 10% on the Guardian's own stake and 3.33% on delegated stake.
- Rewards accrue continuously at the contract level as a numerical reward balance, but they are not automatically added to the user's actual staked ORBS amount. The user must manually claim / settle rewards in TETRA or another official staking interface before those rewards are added to the staked balance and can later be unlocked / withdrawn.
- Unlocking / unstaking is required before the rewarded/staked amount can be moved or transferred.

Because reward rates may change, this should be treated as a dated operational snapshot.

## Custodial Staking Access
User-provided note as of 2026-04-29:

- Beyond personal-wallet on-chain staking, ORBS can also be staked through Bithumb's custodial staking service in Korea.
- Users deposit ORBS into Bithumb and participate with a simple consent flow.
- The advantage is convenience and exchange-side liquidity: no lockup period for trading inside the exchange, so users can buy or sell at any time under Bithumb's service conditions.
- The tradeoff is a lower reward rate, generally around 2–4%, compared with direct on-chain staking.
- Current details should be checked directly at http://bithumb.co.kr/
