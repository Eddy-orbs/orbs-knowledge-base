# Staking Mechanics

## Summary
Orbs의 staking은 단순 토큰 예치가 아니라, Delegator와 Guardian이 ORBS 토큰을 매개로 네트워크 보안과 인센티브 구조에 참여하는 메커니즘입니다. 따라서 이 문서는 기술 개념과 운영 개념의 중간 지점을 설명합니다.

## Main Actors
- Delegator: ORBS를 stake하고 Guardian에게 voting weight를 위임하는 참여자
- Guardian: 네트워크 운영/보안에 기여하는 validator 역할의 참여자

## Core Mechanics
- ORBS 토큰을 기반으로 stake가 이루어짐
- Delegator는 Guardian을 선택해 위임
- Guardian은 네트워크 보안과 운영의 핵심 역할을 수행
- reward distribution은 버전별 PoS 구조에 따라 다를 수 있음
- lockup / unlocking / reward split 같은 요소는 사용자 가이드 문서와 함께 읽어야 함

## Version Sensitivity
- V1, V2, V2.5, V3에 따라 세부 staking mechanics가 달라질 수 있음
- APR, reward split, lockup, Ethereum/Polygon 연계 구조는 특정 버전을 명시해서 설명해야 함

## Relationship to Token Layer
- staking은 ORBS token utility의 핵심 축 중 하나
- fee settlement / staking / Guardian election / rewards는 서로 분리된 기능이 아니라 하나의 incentive system을 이룸

## Related Docs
- `pos-version-comparison.md` for V1/V2/V2.5/V3 differences
- `../06_qna/staking-guide.md` for user-facing operational guidance

## Sources
- https://www.orbs.com/pos/
- https://www.orbs.com/polygon-staking/
- https://www.orbs.com/PolygonStakingFAQs/
- https://orbs-doc.gitbook.io/pos
- https://orbs-doc.gitbook.io/pos/orbs-pos-universe/becoming-the-delegator
- https://orbs-doc.gitbook.io/pos/orbs-pos-universe/becoming-the-guardian
