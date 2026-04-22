# Briefings Layer

This directory contains audience-facing briefing artifacts built on top of the English canonical knowledge base.

## Model
- `en/` is the default English briefing layer.
- `ko/` is the maintained Korean briefing layer.
- Additional languages such as Japanese should be generated on demand first.
- If repeated demand appears for a third language, that language can be promoted into its own maintained briefing subdirectory.

## Rules
- Do not duplicate the full knowledge base by language.
- Keep the canonical source of truth in the English base documents.
- Use briefing files for short delivery formats such as one-liners, 30-second briefs, 2-minute briefs, investor summaries, and short FAQs.
- Keep key protocol and product terms visible in English even in localized briefings when precision matters.

## Suggested Subdirectories
- `en/`
- `ko/`
- Future optional: `ja/`, `zh/`, etc., only when recurring demand justifies maintenance.
