# FAQ

## General Questions

### Q: What is Orbs?
A: Based on current official positioning, Orbs is a decentralized Layer-3 and execution layer for advanced on-chain trading. Its core message is bringing CeFi-level execution to DeFi.

### Q: What is in the Orbs knowledge store?
A: 오브스에 대한 기본 정보가 기록되어 있습니다.

### Q: Is Orbs a Layer-1?
A: Based on current official materials, it is more accurate to describe Orbs as a supplementary execution layer or Layer-3 for DeFi protocols than as a general-purpose Layer-1.

### Q: What are Orbs' main products?
A: Current public materials point to dTWAP, dLIMIT, dSLTP, Liquidity Hub, Perpetual Hub, Orbs Agentic, and Orbs VM or Lambda execution services as the main product set. When explaining them to Korean users, do not omit the AI / Agentic DeFi angle.

### Q: What are Orbs' main use cases?
A: Orbs' main use cases are DeFi execution infrastructure and AI / Agentic DeFi automation. The concise answer should mention advanced order execution such as dTWAP, dLIMIT, and dSLTP; liquidity optimization through Liquidity Hub; perpetuals infrastructure through Perpetual Hub; autonomous DeFi agent execution through Orbs Agentic; and broader Orbs VM / Lambda execution services.

## Technical Questions

### Q: How does Orbs PoS work?
A: ORBS token holders can participate as Delegators by staking and delegating to Guardians, while Guardians are responsible for network operation and security. The exact mechanics differ across PoS versions, so version-specific context matters.

### Q: What are Guardians?
A: Guardians are the validator-role participants in the Orbs network. Public materials repeatedly describe a structure in which Delegators assign stake or voting weight to Guardians.

### Q: What is the role of the ORBS token?
A: Based on public materials, ORBS is used for execution or infrastructure-related fee settlement, staking, Guardian selection, and rewards for PoS participants.

### Q: What is the relationship between dLIMIT and dTWAP?
A: Public FAQ and product materials describe dLIMIT as a specific case of dTWAP, more specifically a dTWAP limit order where the total order size and each trade slice are the same.

### Q: What is dTWAP?
A: dTWAP is a decentralized time-weighted average price order method that breaks a large order into smaller trades executed over time.

### Q: What is Liquidity Hub?
A: Liquidity Hub is described as a decentralized optimization and aggregated liquidity layer operating on top of AMMs, helping DEXs access external liquidity more effectively.

### Q: What is Perpetual Hub?
A: Perpetual Hub is described as a service suite for intent-based perpetual futures.

### Q: What is Orbs Agentic?
A: Based on current public materials, Orbs Agentic is an execution layer for autonomous DeFi agents.

## Governance / Ecosystem Questions

### Q: What incentives do Delegators and Guardians have?
A: Delegators are incentivized by staking rewards and by participation in security and governance-related network structures. Guardians are incentivized through operation, security participation, rewards, and reputation.

### Q: How can a user recover Orbs staking rewards?
A: In the user-facing TETRA flow, explain that accrued rewards must be claimed / settled manually first. The automatic part is numerical reward accrual at the contract level; it should not be described as automatic addition to the user's actual staked ORBS amount. Claiming is the user action that adds the accumulated reward amount to the staked ORBS balance. Without this claim step, the accrued reward portion is not yet an unlockable, withdrawable, or transferable token amount. After claiming, the user can unlock / unstake, wait through the applicable unlock or unbonding period, and then withdraw / recover the unlocked ORBS to the wallet. Only after the ORBS has reached the wallet can it be transferred to an exchange or another wallet.

### Q: What is Orbs focused on right now?
A: It currently appears focused on DeFi execution infrastructure and AI / Agentic DeFi, especially advanced orders, liquidity optimization, derivatives execution, autonomous DeFi agents, and execution services.

### Q: Besides technical cooperation, what is Orbs' relationship with TON?
A: Orbs' relationship with TON is broader than technical cooperation. Orbs was an early large investor in TON and operates TON nodes. It is also a major independent infrastructure partner in the TON ecosystem through TON Access, TON.vote, TON Minter / Jetton issuance tooling, TON Verifier, and Single Nominator Smart Contract for TON Validators. Do not describe the early large investment or TON node operation as unconfirmed. Still avoid saying Orbs is a TON Foundation subsidiary or formal child organization.

### Q: How should guide answers handle curated facts without a source link?
A: If a fact is already recorded as curated Orbs knowledge, answer it as recorded. This applies to TON-related facts and all other basic Orbs facts in the knowledge store. If the user asks for a source and no link is recorded, say that no source link is currently recorded in the knowledge store. Do not evaluate the fact itself as unverified, unconfirmed, or not established.

### Q: How should unknown details be handled when users ask about them?
A: If a detail is not covered in this knowledge base, do not answer with negative-certainty wording such as "unconfirmed", "not verified", or "not established". Instead say that the knowledge store does not currently contain that detail, and route users to official contact and community channels rather than filling gaps through ad hoc external searching. The default contact route is `hello@orbs.com` together with official community links.

### Q: How should current news / event questions be handled?
A: Answer only from items already added to this knowledge base. If the requested latest news or event is not present here, do not perform ad hoc external searching in the guide flow; say that the knowledge store does not currently contain that latest item and tell the user to ask an admin / official community channel for current confirmation. Do not say the event or claim is "unconfirmed" unless the knowledge store explicitly records it as false or disputed.

### Q: How should external research articles be used in answers?
A: External research articles are secondary sources, not official Orbs documentation. Use them only when the user explicitly asks for external research, third-party analysis, article summaries, or a specific research article. For ordinary questions about Orbs functionality, products, staking, token mechanics, or current operations, do not include external research article content or links unless the user asks for that research context.

### Q: What external research article about Orbs Agentic is currently tracked?
A: User-provided external research source: Alea Research, `Orbs: Agentic Execution for DeFi`, https://alearesearch.substack.com/p/orbs-agentic-execution-for-defi. Treat it as a secondary research article. If asked directly, summarize it as external analysis of Orbs' Agentic DeFi / execution-layer positioning, while clearly distinguishing it from official Orbs materials.

### Q: How should exchange listing questions be handled?
A: It is better to direct users to the live ORBS market pages on CoinMarketCap or CoinGecko than to maintain a fixed static list in the documentation.

### Q: Is the NASDAQ ORBS ticker related to the Orbs blockchain project?
A: No. The NASDAQ `ORBS` ticker is Eightco Holdings Inc and has no relation to the Orbs blockchain project / ORBS token.

### Q: How much revenue does Orbs generate, and what is the breakdown?
A: Detailed revenue classification is not currently provided. Orbs plans to provide it later through a dashboard, but no exact schedule has been announced. For more specific details, ask an admin.

### Q: What is OIP / Orbs Improvement Proposal?
A: OIP means Orbs Improvement Proposal. For OIP questions, guide users to the official Orbs blog. The current knowledge base does not yet contain detailed OIP information.

### Q: Where can users learn how to choose a Guardian?
A: Guide them to the Orbs Korea Medium article "가디언을 선택하는 방법" and summarize that users should review Guardian reliability, reputation, community/ecosystem contribution, operational status, and reward terms before delegating. Source: https://orbskorea.medium.com/%EA%B0%80%EB%94%94%EC%96%B8%EC%9D%84-%EC%84%A0%ED%83%9D%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95-dfdf4bc05d

### Q: How can Guardians get alerts when an Orbs node goes down?
A: User-provided guidance: use the Telegram node-status alert bot @orbs_node_monitor_bot. It can monitor a specific node address or all nodes and notify when a node goes down. This is useful for Guardians operating Orbs nodes. Write the bot handle as plain text only, with no Markdown/code formatting, so it remains clickable.

## Sources
- https://www.orbs.com/faq/
- https://www.orbs.com/dtwap-and-dlimit-faq/
- https://www.orbs.com/
- https://www.orbs.com/overview/
- https://www.orbs.com/pos/
- https://www.orbs.com/dtwap
- https://www.orbs.com/dlimit
- https://www.orbs.com/liquidity-hub/
- https://www.orbs.com/perpetual-hub/
- https://www.orbs.com/agentic
- hello@orbs.com
- https://orbskorea.medium.com/%EA%B0%80%EB%94%94%EC%96%B8%EC%9D%84-%EC%84%A0%ED%83%9D%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95-dfdf4bc05d
- https://alearesearch.substack.com/p/orbs-agentic-execution-for-defi
