# Briefing Localization Guide

## Canonical Source
Always treat the English canonical knowledge-base documents as the source of truth.

## Maintained Layers
- English (`en/`): maintained briefing layer
- Korean (`ko/`): maintained briefing layer

## On-Demand Languages
Additional languages such as Japanese should be handled on demand first.

### Recommended Flow for a Third Language
1. Pull the answer from the English canonical docs.
2. Generate a localized briefing artifact for the requested language.
3. Keep core protocol and product terms visible in English when precision matters.
4. If requests for that language become frequent, promote it into a maintained directory such as `ja/`.

## Localization Rules
- Do not create full language-by-language copies of the entire knowledge base.
- Localize briefing outputs, not the entire research base.
- Prefer short, reusable formats such as one-liners, 30-second briefs, 2-minute briefs, investor briefs, and short FAQs.
- If terminology translation becomes sensitive, defer to a future translation standard instead of translating inconsistently.
