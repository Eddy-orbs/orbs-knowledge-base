# Staking Guide

## Summary
This document is a practical participation guide for Orbs PoS. It focuses less on abstract protocol design and more on how users can participate and what they should verify before acting.

## Who Can Participate?
### Delegator
- A regular participant who stakes ORBS and delegates to a Guardian
- Should understand rewards, reward split, lockup conditions, Guardian credibility, and operational status

### Guardian
- A validator-role participant directly involved in network operation and security
- Carries higher technical and operational responsibility
- Should understand node operation and troubleshooting guidance

## Main Entry Points
- Official PoS page: https://www.orbs.com/pos/
- PoS docs: https://orbs-doc.gitbook.io/pos
- TETRA staking dapp: https://staking.orbs.network/
- ORBS Universe Analytics: https://analytics.orbs.network/ethereum/overview/stake
- Network status: https://status.orbs.network/

## Delegator Flow
1. Hold ORBS and prepare a supported network and wallet setup
2. Access TETRA or another official staking tool
3. Review available Guardian candidates
4. Complete staking and delegation
5. Check rewards, lockup conditions, and network status
6. When recovering staking rewards, first claim / settle accrued rewards so they are added to the staked balance
7. Review undelegation, unlock, and withdrawal steps when needed

## Delegator Checklist
- Has the Guardian’s reputation and operational stability been reviewed?
- Is the reward split structure understood?
- Have lockup and unlock conditions been checked?
- Have network fees on Ethereum, Polygon, or the relevant chain been considered?
- Has current operating status been checked on analytics or status pages?

## Guardian Flow
1. Review the official Guardian guide
2. Understand the operational requirements and responsibilities
3. Study node, monitoring, and troubleshooting documentation
4. Complete the Guardian participation process
5. Monitor operational status continuously

## Helpful Tools
- TETRA tutorial: https://www.orbs.com/tetra-orbs-staking-wallet-tutorial/
- Guardian troubleshooting: https://orbs-doc.gitbook.io/orbs-guardian-help
- ORBS PoS Info mobile apps
- ORBS Universe Analytics
- Network Status dashboard

## Live Staked Amount Answering Rule
When asked for the current ORBS staking amount / total staked quantity:

0. First read the local live snapshot: `../07_sources/live/staking-status-snapshot.md`.
   - If the snapshot is fresh enough for the question, answer directly from it.
   - If the snapshot is old or missing, say a fresh Orbs network status check is needed; do not fall back to only the static "1B+ ORBS" fact.
1. The snapshot is generated from the internal network-status JSON feed by inspecting these two fields:
   - `Statuses.Ethereum Contracts Health.StatusMsg`
   - `Statuses.Matic Contracts Health.StatusMsg`
2. Extract the `Total Staked` value from each field.
3. Answer with:
   - Ethereum staked amount
   - Polygon / Matic staked amount
   - Combined total across both networks
4. Do not expose or publish the raw JSON endpoint URL in user-facing answers. Treat it as an internal verification source.
5. Public-facing source wording should refer generally to the Orbs network status / staking status check, not the internal JSON URL.

Example answer shape:
"현재 확인 기준으로 Ethereum에 약 X ORBS, Polygon/Matic에 약 Y ORBS가 스테이킹되어 있으며, 합산 총 스테이킹 수량은 약 Z ORBS입니다."

## Important Cautions
- Reward rules, APR, reward split, and lockup terms may differ across PoS versions
- Official FAQ snippets reference a 14-day locking period in the PoS V3 context, but the exact version scope should be stated carefully when answering
- Locking mechanics changed around 2020, so historical staking guidance should not be mixed with current guidance
- Guardian credibility and operational status should be checked before staking
- For live conditions, prioritize analytics, status, and official docs over generic market sites

## Sources
- https://www.orbs.com/pos/
- https://orbs-doc.gitbook.io/pos
- https://orbs-doc.gitbook.io/pos/orbs-pos-universe/becoming-the-delegator
- https://orbs-doc.gitbook.io/pos/orbs-pos-universe/becoming-the-guardian
- https://orbs-doc.gitbook.io/orbs-guardian-help
- https://staking.orbs.network/
- https://analytics.orbs.network/ethereum/overview/stake
- https://status.orbs.network/

## Current Reward Rates and Reward Handling
As of the user-provided 2026-04-29 update, the current Orbs PoS reward rates and handling are:

### Delegators
- Delegator annualized average reward rate: 6.67%.
- Rewards accrue continuously as a contract-level / numerical reward balance, effectively every block.
- Accrued rewards are **not automatically added to the user's actual staked ORBS amount**.
- The user must manually perform a **claim / settlement** action in TETRA or another official staking interface. This action converts the numerically accrued reward balance into ORBS that is added to the user's staked amount.
- Without this manual claim / settlement step, the accrued reward balance is not yet in a token form that can be unlocked, withdrawn, or transferred.
- To move or transfer the rewarded/staked amount, the user needs to claim / settle the accrued rewards first, then unlock / unstake and withdraw according to the applicable rules.

### Reward Recovery Flow
When a user asks how to recover or take back staking rewards, explain the sequence clearly:

1. **Claim / settle rewards** in TETRA or another official staking interface.
   - This is a manual user action, not an automatic background step.
   - Accrued rewards are only a numerical / contract-level reward balance before claim.
   - Claiming / settlement adds the accumulated rewards to the user's actual staked ORBS balance.
   - If the user skips claim, the reward portion will not become an unlockable / withdrawable token amount.
2. **Unlock / unstake** after the rewards have been reflected in the staked balance.
   - At this point, both the original stake and the claimed reward amount can become part of the recoverable staking balance.
3. **Wait through the applicable unlock / unbonding period**.
   - User-facing answers may mention the commonly referenced ~14-day period where applicable, but should caveat that live rules can differ by PoS version, network, and interface.
4. **Withdraw / recover the unlocked ORBS to the wallet**.
   - Once the ORBS is back in the user's wallet, it can be transferred to an exchange or another wallet.

### Guardians
- Guardian reward rate on the Guardian's own stake: 10%.
- Guardian reward rate on delegated stake: 3.33%.

### User-Facing Explanation
A concise explanation for users: "Current delegator staking rewards are about 6.67% annualized. Rewards accrue continuously as a contract-level reward balance, but they are not automatically added to the actual staked ORBS amount. To recover them, the user must manually claim / settle the rewards in TETRA first; that claim action adds the rewards to the staked balance. Only after that can the user unlock / unstake, wait through the applicable period, and withdraw to the wallet. Once withdrawn to the wallet, the ORBS can be sent to an exchange or another wallet. Guardians receive 10% on their own stake and 3.33% on delegated stake."

### Caution
Reward rates and staking mechanics can change. For live decisions, check the official staking dapp, analytics, and current contract state.

## Custodial Staking via Bithumb
As of the user-provided 2026-04-29 update, ORBS staking is also available through a custodial staking service on Korea's Bithumb exchange, in addition to direct self-custody / on-chain staking.

### Bithumb Custodial Staking
- Users can deposit ORBS into Bithumb and participate in the exchange's staking service with a simple consent flow.
- Main convenience advantage: users do not need to manage a personal wallet or direct on-chain staking process.
- Liquidity / access advantage: there is no lockup period in the exchange context, and users can buy or sell ORBS inside the exchange at any time according to Bithumb's service conditions.
- Tradeoff: the reward rate is lower than direct on-chain staking, generally around 2–4% according to the user-provided note.
- For current details, users should refer directly to Bithumb: http://bithumb.co.kr/

### User-Facing Framing
A concise explanation for users: "ORBS can be staked directly on-chain from a personal wallet, or via Bithumb's custodial staking service in Korea. Bithumb is simpler and has no exchange-side lockup for trading, but the reward rate is typically lower, around 2–4%, compared with direct on-chain staking."

### Caution
Custodial staking means the exchange controls custody while assets are deposited. Users should check Bithumb's current terms, reward rate, eligibility, fees, and service risks before participating.
