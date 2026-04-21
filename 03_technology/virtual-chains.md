# Virtual Chains

## Summary
GitHub/spec 자료 기준 virtual chains는 Orbs 노드 아키텍처의 핵심 개념입니다. 공개 설명에 따르면 Orbs 노드의 중심에는 virtual chains 집합이 있으며, 이들은 독립적인 blockchain instance로서 smart contract를 실행하고 consensus를 구현합니다.

## Explanation
- Virtual chains are described as standalone blockchain instances
- They execute smart contracts
- They implement Helix / Lean Helix consensus in the protocol context
- They appear to be central to the internal architecture of Orbs nodes

## Why It Matters
- virtual chains는 Orbs의 초기/중기 기술 정체성을 이해하는 데 중요합니다
- 현재 public-facing L3 execution narrative와, protocol-level virtual-chain architecture를 연결하는 다리 역할을 합니다
- app-specific or service-specific execution isolation / modularity를 설명하는 단서가 될 수 있습니다

## Related Components
- Orbs node
- orbs-network-go
- orbs-spec
- management-service
- Boyar / Boyarin related orchestration concepts

## Open Questions
- 현재 L3 execution products와 virtual chains의 관계를 공식 문서 기준으로 어떻게 가장 정확히 설명할 수 있는가?
- virtual chains가 today-facing product narrative에서 얼마나 직접적으로 드러나는가?

## Sources
- https://github.com/orbs-network/orbs-spec
- https://github.com/orbs-network/orbs-network-go
- https://github.com/orbs-network/management-service
- https://github.com/orbs-network/boyarin
