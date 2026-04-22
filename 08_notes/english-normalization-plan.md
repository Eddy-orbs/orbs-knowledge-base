# English Canonical Normalization Plan

## Goal
Normalize the base Orbs knowledge-base documents into English canonical form, while keeping Korean and other non-English content as a separate delivery layer.

## Priority 1: High-leverage Q&A and overview files
These are the most likely to be reused directly in assistant answers, briefings, and retrieval flows.

- `README.md`
- `00_overview/orbs-summary.md`
- `00_overview/timeline.md`
- `06_qna/faq.md`
- `06_qna/investor-questions.md`
- `06_qna/technical-questions.md`
- `06_qna/executive-briefs.md`
- `06_qna/staking-guide.md`
- `06_qna/response-policy.md`

## Priority 2: Core technology and business reference docs
These influence explanation quality and terminology consistency.

- `03_technology/pos-version-comparison.md`
- `03_technology/staking-mechanics.md`
- `03_technology/current-architecture.md`
- `03_technology/virtual-chains.md`
- `05_business/token-overview.md`
- `05_business/token-distribution-notes.md`
- `05_business/token-economics.md`
- `05_business/multichain-token-map.md`
- `05_business/exchange-listings.md`
- `05_business/business-model.md`
- `05_business/adoption-strategy.md`

## Priority 3: History and use-case content
Important, but lower urgency than top-level answer surfaces and key protocol/token docs.

- `02_history/early-stage.md`
- `02_history/launch-period.md`
- `02_history/current-state.md`
- `02_history/growth-phase.md`
- `04_use-cases/use-cases-overview.md`
- `04_use-cases/defi.md`
- `04_use-cases/enterprise.md`
- `04_use-cases/loyalty.md`
- `04_use-cases/rwa.md`
- `04_use-cases/other-verticals.md`
- `01_founders/founders-overview.md`
- `05_business/partners.md`
- `05_business/ecosystem-incentives.md`

## Priority 4: Training / internal-use artifacts
Useful to normalize, but less urgent if the core knowledge documents are already English.

- `09_training/glossary.md`
- `09_training/evaluation-checklist.md`
- `09_training/prompt-examples.md`
- `09_training/answer-style.md`
- `06_qna/quiz-bank.md`
- `06_qna/answer-key-outline.md`

## Suggested Execution Order
1. Normalize Priority 1 files first.
2. Normalize terminology-sensitive protocol/token docs in Priority 2.
3. Convert narrative/history/use-case docs in Priority 3.
4. Clean training/support artifacts last.

## Translation / Language Rules During Cleanup
- Preserve English source terms for protocol roles, products, and technical components.
- Avoid mixed-language drafting in the canonical file.
- If a Korean explanation is useful later, place it in a separate Korean briefing or summary document.
- If a term requires a fixed Korean rendering, defer to the future terminology translation standard instead of improvising per file.
