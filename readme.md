# Cold Email Analyzer

> Paste any cold email. Get scored across 7 dimensions. Get a rewrite that converts.

**[→ Live Demo](https://iamtheaak.github.io/cold-emaill-analyzer/)**

---

Most cold emails fail for the same structural reasons not bad luck. This tool identifies those reasons, scores them, and generates a rewrite.

## What it analyzes

| Dimension | What it checks |
|-----------|---------------|
| **Subject Line** | Specificity, curiosity gap, spam trigger words, length |
| **Personalisation** | Evidence of actual research: posts, product details, company news |
| **Clarity of Ask** | Whether CTA is specific, time-bound, and low-friction |
| **Social Proof** | Concrete stats, outcomes, and credibility signals |
| **Length** | Word count ideal range is 60–120 words |
| **Spam Safety** | Trigger words that hurt deliverability and signal low quality |
| **Value-First** | Whether the email opens for them or about you |

## Output

- Overall score (0–100) with tier classification
- Per-dimension scores with specific fix instructions
- Word-level annotation highlights power words (green), spam words (red), hedge words (yellow)
- 4-part rewrite: subject line → opener → credibility → CTA
- Best-practice checklist (8 items)
- Spam trigger word detection with exact words flagged

## The cold email rules baked in

- **Never open with "I"** open with a specific observation about them
- **One CTA, time-specific** "15 minutes this Thursday?" not "let me know"
- **One stat** not a client list, one concrete outcome
- **60–120 words** anything longer gets skimmed or ignored
- **Avoid "opportunity", "collaboration", "synergy"** generic signals low effort

## Stack

Pure HTML, CSS, JavaScript. Regex-based word analysis. No API calls, no data stored.

## Why I built this

After running 3 cold outreach campaigns (at Cosmofeed and personally), I noticed the same mistakes appearing across emails: generic subjects, self-focused openers, vague asks. I wanted a tool that made the structural rules visible and testable, not just documented in a blog post.

---

Built by [Ayush Khandual](https://iamtheaak.github.io) · IIM Bangalore · 2026
