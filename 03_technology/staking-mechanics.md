# Staking Mechanics

## Summary
Staking in Orbs is not just passive token deposit behavior. It is the mechanism through which Delegators and Guardians participate in network security and incentives using the ORBS token. This document sits between abstract technical explanation and practical operating guidance.

## Main Actors
- Delegator: a participant who stakes ORBS and delegates voting weight to a Guardian
- Guardian: a validator-role participant contributing to network operation and security

## Core Mechanics
- Staking is built around the ORBS token
- Delegators choose a Guardian and delegate to that Guardian
- Guardians play a central role in security and network operation
- Reward distribution can differ by PoS version
- Lockup, unlocking, and reward-split details should be read together with the user-facing staking guide

## Version Sensitivity
- Detailed staking mechanics may differ across V1, V2, V2.5, and V3
- APR, reward split, lockup rules, and Ethereum or Polygon interactions should always be explained with explicit version scope

## Relationship to Token Layer
- Staking is one of the central utility layers of the ORBS token
- Fee settlement, staking, Guardian election, and rewards are not isolated functions, they form a single incentive system

## Related Docs
- `pos-version-comparison.md` for V1, V2, V2.5, and V3 differences
- `../06_qna/staking-guide.md` for user-facing operational guidance

## Sources
- https://www.orbs.com/pos/
- https://www.orbs.com/polygon-staking/
- https://www.orbs.com/PolygonStakingFAQs/
- https://orbs-doc.gitbook.io/pos
- https://orbs-doc.gitbook.io/pos/orbs-pos-universe/becoming-the-delegator
- https://orbs-doc.gitbook.io/pos/orbs-pos-universe/becoming-the-guardian

## Current Reward Accounting Notes
As of the user-provided 2026-04-29 update, current Orbs staking rewards should be described as follows:

- Delegator reward rate: 6.67% annualized average reward rate for staked ORBS.
- Reward accrual method: rewards accrue continuously as a contract-level / numerical reward balance, effectively every block.
- Reward settlement method: accumulated rewards must be claimed / settled manually by the user through TETRA or another official staking interface; only after this manual action are they added to the actual staked amount.
- Transferability: accrued-but-unclaimed rewards are not yet unlockable, withdrawable, or transferable token amounts. To move them, the user should first claim / settle rewards into the staked balance, then unlock / unstake, wait through the applicable unbonding period, and withdraw the unlocked ORBS to the wallet.
- Guardian reward rate: Guardians receive 10% on their own staked amount and 3.33% on delegated stake delegated to them.

### Claim, Unlock, and Withdrawal Sequence
For user-facing support, avoid implying that rewards can be sent directly from the accrual state to an exchange or external wallet. The practical sequence is:

1. Claim / settle accrued rewards manually in TETRA or an official staking interface.
2. Confirm the claimed rewards have been reflected in the staked ORBS amount.
3. Unlock / unstake the relevant amount.
4. Wait for the applicable lockup / unbonding period.
5. Withdraw / recover the unlocked ORBS to the wallet.
6. Transfer to an exchange or another wallet only after the withdrawal has completed.

Important clarification: do not describe reward accrual as automatic addition to the user's staked balance. The automatic part is the numerical reward accrual. The conversion of that accrued balance into actual staked ORBS requires a manual claim / settlement transaction by the user.

These figures should be treated as current user-provided operational parameters and should be rechecked against official staking analytics or contracts before being used in time-sensitive financial guidance.

### Latest Recorded Total Staked Quantity
For current or latest recorded total staked quantity answers, use the tracked staking count table in `../03_token/staking-tracked-counts.md`.

User-facing answers should provide the snapshot date, Ethereum amount, Polygon / Matic amount, and combined total from the latest recorded Google Sheet row. Do not use the older network-status live-check snapshot rule for guide answers.

## Custodial Staking Option
In addition to direct self-custody / on-chain staking, a custodial staking option is available through Korea's Bithumb exchange according to the user-provided 2026-04-29 update.

- Users deposit ORBS into Bithumb and opt into the exchange staking service.
- This route is operationally simpler than direct wallet-based staking.
- Bithumb's exchange-side staking service is described as having no lockup period for exchange trading, allowing users to buy or sell ORBS within the exchange at any time under Bithumb's service conditions.
- The tradeoff is a lower reward rate, generally around 2–4%, compared with direct on-chain staking.
- Current terms should be checked directly at http://bithumb.co.kr/

This should be described as custodial staking, distinct from direct on-chain staking.
