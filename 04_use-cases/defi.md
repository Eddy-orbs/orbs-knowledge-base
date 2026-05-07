# DeFi Use Cases

## Summary
The clearest Orbs use cases sit inside DeFi, especially around advanced order execution and trading infrastructure. Public materials describe dTWAP, dLIMIT, dSLTP, Liquidity Hub, and Perpetual Hub as products aimed at bringing DeFi trading UX closer to CeFi-grade execution.

## Main DeFi Primitives
- dTWAP: decentralized time-weighted average price orders
- dLIMIT: decentralized limit orders with on-chain execution guarantees
- dSLTP: decentralized stop-loss and take-profit orders with on-chain execution guarantees
- Liquidity Hub: liquidity optimization and aggregation for DEXs
- Perpetual Hub: infrastructure for intent-based perpetual futures
- SPOT / Spot Advanced Swap Orders: an agent-native advanced swap-order interface for AI agents and wallet-enabled assistants

## Working Interpretation
Orbs appears to provide DeFi protocols with order types and execution logic that are difficult to implement using only native smart contracts. In the DeFi use-case context, its value lies less in inventing entirely new financial products and more in upgrading the execution layer of existing DeFi trading experiences.

## Sources
- https://www.orbs.com/overview/
- https://www.orbs.com/dtwap
- https://www.orbs.com/dlimit
- https://www.orbs.com/dsltp/
- https://www.orbs.com/liquidity-hub
- https://www.orbs.com/perpetual-hub

## Orbzy: Third-Party Agentic DeFi Interface
Orbzy is a late-April 2026 third-party DeFi agent use case built by an independent team using Web3Agent on Orbs Protocol infrastructure. Orbs clarified on X that Orbzy is not an official Orbs product, but a third-party contribution powered by the Orbs execution layer.

### What Orbzy Demonstrates
- A natural-language interface for advanced DeFi execution: users describe the desired trade in plain English.
- Orbs-powered execution primitives exposed through an agent interface, including dTWAP, dLIMIT, and Liquidity Hub.
- Transaction simulation and user review before approval.
- Initial supported chains listed by the Orbzy app: Base, Polygon, BNB Smart Chain, and Linea.
- The broader ecosystem implication is that Orbs infrastructure can be used by external builders as a backend/execution layer for agentic DeFi applications.

### Caution
- Orbzy should be described as a third-party beta app, not as an official Orbs product.
- Because it is beta software, user-facing explanations should avoid implying production-grade guarantees beyond what official sources state.

### Sources
- https://x.com/orbs_network/status/2048795601156898948
- https://x.com/orbs_network/status/2048795607691673994
- https://x.com/orbs_network/status/2048798278603399389
- https://orbzy.web3agent.fi/


## SPOT: Agent-Native Advanced Swap Orders
SPOT, announced publicly on 2026-05-01, is Orbs' agent-native DeFi trading interface for advanced swap orders. It is designed so an AI agent can read raw markdown documentation and structured parameters, construct an order, guide wallet approval/signing, and submit a non-custodial order payload without relying on a human-oriented frontend.

### Supported Order / Execution Shapes
- Gasless market swap
- Limit order
- TWAP
- Stop-loss
- Take-profit
- Delayed-start swap
- Recurring / chunked execution patterns

### Strategic Meaning
- SPOT extends Orbs' existing DeFi execution products into the AI-agent market.
- It connects the earlier "CeFi-level execution for DeFi" positioning with an "AI agents can execute DeFi intents" narrative.
- It should be described as an execution interface / order-construction layer, not as a custodial trading bot.
- The strongest explanation is: AI agents can decide or translate intent, while Orbs' L3 execution layer provides advanced order infrastructure.

### Caution
- Avoid overstating live adoption until there are public usage metrics specific to SPOT.
- Agentic DeFi introduces extra risk around permissions, approvals, wrong objectives, exploit exposure, and policy guardrails; user-facing explanations should keep the non-custodial signing/approval step clear.

### Sources
- https://www.benzinga.com/pressreleases/26/05/52224441/orbs-launches-spot-the-first-defi-trading-interface-built-natively-for-ai-agents
- Local Spot skill bundle: `~/.openclaw/workspace/skills/spot-advanced-swap-orders/SKILL.md`

## The Orbs Agentic Challenge
The Orbs Agentic Challenge is a May 2026 trading campaign that demonstrates Orbs' agent-native DeFi positioning in a user-facing format. The campaign asks users to execute at least one trade through Orbs Agentic, with support highlighted for order styles such as TWAP, limit orders, stop-loss, swaps, and take-profit.

### Campaign Structure
- Overall window: 2026-05-04 to 2026-05-24, UTC.
- Phase 1, 2026-05-04 to 2026-05-10: one Orbs Agentic trade enters the user into a 500 USDC raffle, with 10 random winners receiving 50 USDC each.
- Phase 2, 2026-05-11 to 2026-05-24: volume leaderboard prizes plus a lucky draw. The top volume trader receives approximately 599 USDC, 2nd receives 200 USDC, 3rd receives 100 USDC, and 10 random Phase 2 participants receive 50 USDC each.
- The stated total prize pool is more than 1,500 USDC.

### Strategic Meaning
- The campaign reinforces that Orbs Agentic is being positioned as the execution layer between AI agents and DeFi protocols.
- The official campaign page describes the flow as non-custodial and gasless for the agent, with trades verified by a decentralized cosigned oracle before execution.
- It is a marketing / participation campaign, not a separate protocol primitive; describe it as evidence of Orbs' agentic DeFi go-to-market activity rather than as a standalone product.

### Sources
- https://www.orbs.com/challenge/
- https://www.orbs.com/ko/challenge/
- https://x.com/orbs_network/status/2051583930206216517
