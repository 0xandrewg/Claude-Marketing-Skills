# Tone Filter

The quality control layer. Scans any draft and catches corporate filler, AI slop, hype language, vague outcomes, and formatting problems. Returns flagged issues, a clean rewrite, and a publish readiness score.

## What It Does

- Scans drafts against 10 categories of banned/flagged content (80+ phrases)
- Returns every flagged issue with a specific fix
- Rewrites the full post with all issues resolved
- Gives a 1-10 publish readiness score
- Catches formatting problems: em dashes, emoji spam, long paragraphs, multiple CTAs

## How to Load It

1. Create a new Claude Project (or add to an existing one)
2. Go to Project Knowledge > Add content
3. Copy the entire contents of `SKILL.md` and paste it in

## How to Customize

### Add industry-specific slop
Every industry has its own version of corporate filler. Finance has "synergies" and "alpha generation." Healthcare has "patient-centric solutions." Add your industry's worst offenders to the relevant categories.

### Adjust strictness
The default catches everything. If you want a lighter touch (e.g., allowing occasional em dashes or more emoji), edit the Formatting Problems section.

### Add your own pet peeves
If there's a phrase you personally hate seeing in your content, add it to the list. The filter is only as good as the avoid list it runs against.

## Example Usage

**You:** Check this:

"I'm excited to announce that our team has been leveraging AI to drive efficiency across our marketing stack. This game-changing approach has helped us unlock unprecedented capabilities in content creation. Don't miss our upcoming webinar to learn how to supercharge your workflow!"

**Claude:**

Issues Found: 8

1. "I'm excited to announce" (Category: Influencer Tone / Corporate)
2. "leveraging AI" (Category: Generic Marketing)
3. "drive efficiency" (Category: Vague Outcome)
4. "game-changing" (Category: AI Hype)
5. "unlock unprecedented capabilities" (Category: AI Hype)
6. "Don't miss our upcoming webinar" (Category: Empty CTA)
7. "learn how to" (Category: Weak Educational)
8. "supercharge your workflow" (Category: AI Hype)

Clean Version:
"We rebuilt our content workflow with AI last month. It cut our production time from 12 hours a week to about 3. Here's exactly what we changed and what broke along the way. Full breakdown in the comments."

Publish Readiness: 8/10

## Works Well With

- **Post Writer**: Write the post, then filter it
- **Hook Writer**: Run hooks through the filter too (hooks can contain slop)
- **Spicy Take Generator**: Even spicy takes need a quality check
