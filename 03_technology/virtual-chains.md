# Virtual Chains

## Summary
Based on GitHub and specification materials, virtual chains are a core concept in the internal architecture of Orbs nodes. Public descriptions indicate that the center of an Orbs node is a set of virtual chains, each functioning as an independent blockchain instance that executes smart contracts and participates in consensus.

## Explanation
- Virtual chains are described as standalone blockchain instances
- They execute smart contracts
- They implement Helix or Lean Helix consensus in the protocol context
- They appear to be central to the internal architecture of Orbs nodes

## Why It Matters
- Virtual chains are important for understanding the earlier and protocol-level technical identity of Orbs
- They help connect the current public-facing L3 execution narrative with the deeper protocol architecture
- They may provide useful clues for explaining service isolation, modularity, or app-specific execution structure

## Related Components
- Orbs node
- `orbs-network-go`
- `orbs-spec`
- `management-service`
- Boyar or Boyarin orchestration-related concepts

## Open Questions
- How should the relationship between current L3 execution products and virtual chains be explained using official language?
- How directly do virtual chains still appear in the current product-facing narrative?

## Sources
- https://github.com/orbs-network/orbs-spec
- https://github.com/orbs-network/orbs-network-go
- https://github.com/orbs-network/management-service
- https://github.com/orbs-network/boyarin
