# Dutton Digital Blog Guidelines

## Audience

- Local business owners (cafes, shops, tradespeople)
- Users/consumers affected by the same issues
- Non-technical readers

## Tone

- Down to earth and conversational, not corporate
- Informative without being preachy
- Acknowledge trade-offs rather than presenting one-sided arguments
- Avoid sensationalism, but also avoid being too dry or clinical
- Keep it readable and personable — not a white paper
- British English, no Americanisms (colour not color, organisation not organization)

## What to avoid

- Dramatic one-liners ("This is broken.", "Welcome to modern software.")
- Clichés ("There's no such thing as free.", "You're the product.")
- Rhetorical gotchas ("You know what that's called? Spam.")
- Dramatic section headers ("The app fantasy", "The dependency trap")
- Stacked short punchy sentences for effect
- Too many rhetorical questions
- Sarcasm
- Overuse of emphasis (bold, italics)

## Structure

- 300-350 words ideal (1.5-2 min read)
- Clear section headers (descriptive, not dramatic)
- End with practical advice or questions to consider
- CTA varies: link to posts, email contact, or link to services

## Citations

- Specific factual claims must be backed by reliable sources
- Add a **References** section at the end of the post with numbered links
- Use markdown reference-style links for inline citations (e.g. `[claim][1]`)
- General observations and industry patterns don't require citations

## Content alignment

Our approach favours standardised, structured data that users control. When discussing platforms or data portability:
- Platform lock-in and lack of data export = problematic
- Open formats and structured data = beneficial for accessibility and portability
- Don't criticise standardisation itself

## Frontmatter

```toml
+++
title = "Title in sentence case"
date = YYYY-MM-DD

[extra]
author = "Louis Dutton"

[taxonomies]
tags = ["ai-assisted"]
+++
```

All posts currently use the "ai-assisted" tag.
