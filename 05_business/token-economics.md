# Token Economics

## Summary
Based on public materials, the ORBS token is used for network-fee settlement, staking, Guardian selection, and rewards for PoS participants. In the currently collected material, ORBS appears as an Ethereum-based ERC-20 token, while the staking structure is described in a broader multi-chain context spanning Ethereum and later Polygon.

## Token Utility
- Settlement of fees related to application execution or infrastructure usage
- Staking
- Election of Guardians, the validator-role participants
- Rewards for PoS participants

## Staking / Incentive Layer
- Delegators stake ORBS and assign voting weight to Guardians
- Guardians secure the network and participate in consensus and operations
- Public materials describe ORBS as the incentive layer of the PoS universe

## Distribution / Rewards Notes
- Public source snippets mention historical reward allocations such as annual ORBS reward pools
- Public FAQ snippets for PoS V3 mention a fixed APR model, but this should be interpreted with explicit version scope
- Exact tokenomics should be versioned because V1, V2, and V3 mechanics may differ

## Important Notes
- Token economics should be separated into base utility, staking incentives, market or supply snapshot, and version-specific staking mechanics
- See also `token-overview.md` for supply and market framing and `exchange-listings.md` for listing references
- Direct tokenomics or whitepaper extraction is still needed for more precise supply and emissions language

## Sources
- https://www.orbs.com/Orbs-A-Re-introduction/
- https://www.orbs.com/pos/
- https://www.orbs.com/polygon-staking/
- https://www.orbs.com/rewards-distribution/
- https://www.orbs.com/PolygonStakingFAQs/
- https://www.orbs.com/optimizing-ethereum-gas-costs-for-orbs-delegators/

## DAO / Season 1 Tokenomics
In April 2026, Orbs announced that the first phase of Orbs DAO governance will include a Season 1 tokenomics vote. Public descriptions indicate that the community is expected to decide how net protocol revenue is allocated across categories such as token burns, staking rewards, liquidity, and reserves.

This should be treated as an announced governance direction rather than finalized tokenomics until the actual proposals and vote outcomes are available.

## April 2026 DAO Governance Scope
- Protocol revenue allocation
- Token economics
- Network upgrades
- Guardian/validator oversight
- Ecosystem grants

## Sources
- https://www.orbs.com/orbs-dao-the-next-step/
- https://chainwire.org/2026/04/16/orbs-advances-dao-rollout-to-decentralize-protocol-governance/
- https://crypto-economy.com/orbs-launches-dao-handing-governance/

## Current PoS Reward Rates
As of the user-provided 2026-04-29 update, current Orbs PoS reward rates are:

- Delegators: 6.67% annualized average reward rate on staked ORBS.
- Guardians: 10% on the Guardian's own staked amount.
- Guardians: 3.33% on delegated stake.

Reward accrual is described as continuous contract-level accrual, effectively every block, but this is a numerical reward balance rather than automatic addition to the user's actual staked ORBS amount. The user must manually claim / settle the accrued rewards in TETRA or another official staking interface; only then are the rewards added to the staked amount. Moving or transferring the rewarded/staked amount requires this claim / settlement step first, followed by unlocking / unstaking, the applicable waiting period, and withdrawal according to the staking rules.

These reward-rate figures should be dated when used and treated as current operational parameters, not immutable tokenomics.

## Source Note
- User-provided Orbs PoS reward update (2026-04-29)

## Custodial Staking via Bithumb
As of the user-provided 2026-04-29 update, ORBS holders in Korea may also access a custodial staking service through Bithumb.

- Bithumb staking is custodial: users deposit ORBS on the exchange and participate through Bithumb's service flow.
- It is simpler than direct self-custody / on-chain staking and does not require users to manage staking contracts directly.
- It is described as having no lockup period in the exchange context, allowing immediate buying or selling inside Bithumb under the exchange's service conditions.
- The reward rate is lower than on-chain staking, generally around 2–4% according to the user-provided note.
- For current details, refer to Bithumb: http://bithumb.co.kr/

This should be framed as a convenience/liquidity tradeoff rather than as equivalent to direct on-chain staking.

### Bithumb ORBS Flexible Staking Event Snapshot
As of user-provided image attachments interpreted on 2026-05-07, Bithumb is scheduled to run "코인 이자받기(스테이킹) 오브스(ORBS) 자유형 이벤트" promotions from 2026-05-08 15:00:00 to 2026-05-21 23:59:59 KST.

- Event type: exchange-side flexible coin-interest / staking event for ORBS deposits.
- Event 1 participation: agree to and maintain Bithumb's flexible coin-interest / staking service, deposit ORBS during the event period, increase ORBS net deposit, and hold ORBS until the event end time.
- Event 2 participation: agree to and maintain Bithumb's flexible coin-interest / staking service, buy ORBS on Bithumb during the event period, increase ORBS net purchase, and hold ORBS until the event end time. Eligible pair: ORBS/KRW.
- Reward basis: ORBS net-deposit ranking for Event 1 and ORBS net-purchase ranking for Event 2 during the event period.
- Reward tiers: ranks 1–50 receive ORBS worth KRW 130,000; ranks 51–450 receive ORBS worth KRW 50,000; ranks 451–1,000 receive ORBS worth KRW 20,000.
- Net deposit formula: event-period total sum of `(deposit quantity - withdrawal quantity)`.
- Net purchase formula: event-period total sum of `(buy quantity - sell quantity)`.
- Payout date stated in the second image: during Friday, 2026-05-29.
- Users may participate in both Event 1 and Event 2.
- Public notice link: not yet available; add the official Bithumb link once provided.

This event should be treated as a Bithumb promotional / custodial exchange event, not as a change to Orbs protocol-level staking rewards or tokenomics.
