# Language Policy

## Core Decision
The canonical language of the Orbs knowledge base is English.

## Rationale
- Most official Orbs source material is in English.
- English reduces drift between source wording and internal documentation.
- English is more reusable for external sharing, AI retrieval, and cross-border collaboration.
- Full bilingual duplication would create unnecessary maintenance overhead.

## Operating Model
- Core knowledge documents should be maintained in English.
- Korean and other non-English materials should be handled as a separate summary / briefing / delivery layer.
- The knowledge layer and the audience-delivery layer should not be mixed unnecessarily.

## Terminology Rule
- Product names, protocol roles, and technical terms should default to the English source form.
- If a Korean or other non-English explanation is needed, keep the original English term visible.
- If terminology translation becomes important for repeated use, create a dedicated translation standard later rather than translating ad hoc in each document.

## Practical Guidance
- Prefer English for `00_overview` to `09_training` base files.
- Prefer Korean-only files for short briefs, local summaries, or user-facing delivery artifacts.
- Avoid mixed-language drafting in the same base document whenever possible.

## Future Work
- Add a translation standard for terms that require fixed Korean or non-English renderings.
- Optionally create Korean briefing templates that depend on the English canonical docs.
