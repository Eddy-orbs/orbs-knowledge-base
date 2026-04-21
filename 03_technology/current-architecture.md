# Current Architecture

## Summary
현재 공개 자료 기준 Orbs는 EVM 기반 L1/L2 및 다른 체인 위에서 작동하는 decentralized Layer-3 execution layer로 설명하는 것이 가장 자연스럽습니다. 핵심 메시지는 유동성을 새 체인으로 옮기지 않고도, 기존 체인/프로토콜 위에 복잡한 logic과 execution services를 얹는다는 점입니다.

## Components
- Layer-3 execution layer
- ORBS token incentive layer
- PoS Guardians / Delegators
- Orbs VM
- Orbs Lambda
- Product protocols such as dLIMIT, dTWAP, dSLTP, Liquidity Hub, Perpetual Hub, Agentic

## Architectural Characteristics
- Enhances existing chains rather than replacing them
- Allows complex logic to be implemented on a decentralized stack without moving liquidity to a new chain
- Uses execution services as a supplementary backend for DeFi protocols
- Public GitHub/spec material suggests virtual chains remain an important architectural concept in the protocol / node layer

## Differences vs Early Architecture
- Earlier Orbs materials emphasized hybrid blockchain architecture, PoS, and virtual-chain-based protocol design
- Current public messaging is much more explicitly focused on L3 execution for DeFi
- VM/Lambda and productized execution services now sit much closer to the center of the narrative

## Sources
- https://www.orbs.com/overview/
- https://www.orbs.com/Orbs3.0/
- https://www.orbs.com/Announcing-Orbs-V4/
- https://www.orbs.com/execution-services/
- https://www.orbs.com/Introducing-Orbs-Agentic/
- https://github.com/orbs-network/orbs-spec
