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
