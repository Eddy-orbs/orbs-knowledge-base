# PoS Version Comparison

## Summary
이 문서는 Orbs PoS V1, V2, V2.5, V3의 차이를 빠르게 파악하기 위한 비교 메모입니다. 공식 공개 자료를 우선 사용했지만, 일부 시점/명칭은 서로 다른 공식 글에서 약간 다르게 표현될 수 있으므로 최종 표준 연표는 추가 검증이 필요합니다.

## High-Level Evolution
- V1: 메인넷 초기 PoS 구조, Ethereum을 외부 oversight/security layer로 활용하는 hybrid 접근
- V2: Age of Guardians, staking contracts를 Ethereum에 fully deploy하며 Guardian 역할 강화
- V2.5: rewards distribution, self-delegation, gas optimization, Guardian/delegator operational model 개선
- V3: Ethereum + Polygon 기반 multi-chain staking, fixed APR 및 구조 조정

## Comparison Table
| Version | 핵심 포지션 | 주요 특징 | 운영/경제 포인트 |
|---|---|---|---|
| V1 | Mainnet launch era PoS | Hybrid blockchain 개념 도입, Ethereum을 base layer oversight/security에 활용 | 초기 1년 운영 모델의 출발점 |
| V2 | Age of Guardians | PoS staking contracts를 Ethereum에 fully deploy, Guardians가 더 적극적 역할 수행 | Guardian 중심 PoS 구조 강화 |
| V2.5 | V2 개선판 | protocol-level automated reward distribution, Guardians가 delegator rewards split 조정, delegator claim schedule 유연화, gas-cost reduction architecture, minimum self-delegation requirement | reward sustainability와 운영 효율 개선 |
| V3 | Multi-chain staking | Ethereum + Polygon 동시 staking 지원, single validator node with multi-network support, fixed 10% APR reference, V2와 유사하나 중요한 조정 포함 | 낮은 가스비 환경 확장, reward allocation 재조정 |

## Version Notes
### V1
- 2019 mainnet launch와 함께 등장
- hybrid blockchain 구조의 초기 형태로 설명됨
- Ethereum을 Orbs PoS의 외부 oversight 및 추가 security layer처럼 활용했다는 공식 설명이 존재

### V2
- Age of Guardians로 불림
- staking contracts의 Ethereum fully-deployed 구조가 핵심 변화로 반복 언급됨
- Guardian의 역할과 경제적 정렬을 강화하는 방향

### V2.5
- 공식적으로 중요한 중간 업그레이드
- automated rewards distribution
- Guardian이 delegator rewards split 조정 가능
- delegator가 보상 수령 시점을 스스로 관리 가능
- 추가 PoS 구성요소를 Ethereum으로 이동
- self-delegation minimum requirement 도입
- gas-cost reduction architecture 반영
- sustainable reward rate를 지향

### V3
- multi-chain staking on Ethereum and Polygon
- 공식 FAQ/announcement 기준 fixed 10% APR 언급
- Guardians는 단일 validator node를 운영하면서 양쪽 네트워크를 지원할 수 있다는 설명 존재
- 네트워크별 self-stake requirement는 별도로 존재할 수 있음
- 일부 시점에는 self-stake requirement 제거 또는 재도입 논의/변경이 있었음

## Important Ambiguities
- 일부 공식 글은 V2 시점을 2019년 11월 launch로 설명하고, 다른 글은 broader Orbs 3.0 retrospective 문맥에서 다소 다르게 표현함
- V2와 V2.5 경계는 백서/블로그/운영 공지마다 강조점이 다름
- V3 이후 self-stake requirement는 한 번의 단순 규칙이 아니라 governance 변경 이력까지 함께 봐야 정확함
- lock period, reward split, APR은 버전별로 다르므로 한 문장으로 뭉뚱그리면 위험함

## Recommended Usage
- 일반 소개용: V1 → V2 → V2.5 → V3 진화 흐름만 사용
- 투자자/리서치용: reward model, self-stake, gas, multi-chain 범위를 버전별로 분리 설명
- 운영 가이드용: 반드시 현재 live rules와 historical version notes를 구분

## Sources
- https://www.orbs.com/Orbs3.0/
- https://www.orbs.com/white-papers/orbs-pos-v2-the-age-of-guardians/
- https://www.orbs.com/orbs-pos-v2-5-official-launch/
- https://www.orbs.com/orbs-pos-v2-5-the-age-of-guardians-is-here/
- https://www.orbs.com/PolygonStakingDate/
- https://www.orbs.com/PolygonStakingFAQs/
- https://www.orbs.com/polygon-staking/
- https://www.orbs.com/Reinstating-Guardians-Self-Stake-Requirement/
- https://www.orbs.com/Polygon-tech/
