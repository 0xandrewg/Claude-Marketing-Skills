# Spicy Take Generator

Takes a news story, trend, or topic and produces contrarian LinkedIn posts that wrap real insight inside humor and internet culture. Built for the Timeline Roast and Spicy Takes content pillars.

## What It Does

- Takes any tech/AI/crypto/startup news and finds the contrarian or absurd angle
- Writes posts that follow the 60/40 rule (fun wrapper, real insight underneath)
- Supports multiple formats: timelines, translations, comparisons, list stacks, fake profiles
- Applies tone rules: punch up, laugh with the audience, troll the platform not the people
- Runs against the master avoid list

## How to Load It

1. Create a new Claude Project (or add to an existing one)
2. Go to Project Knowledge > Add content
3. Copy the entire contents of `SKILL.md` and paste it in

## How to Customize

### Adjust the 60/40 ratio
The default is 60% humor, 40% substance. If your audience wants more depth, tell Claude "shift to 50/50" or "more substance, less joke." If you want pure entertainment, say "go full shitpost."

### Add your industries
The default covers tech, AI, crypto, and startups. If you're in healthcare, finance, or another vertical, add industry-specific examples to the tone guidelines section.

### Change the troll level
The default is "slightly trolling." If your brand is edgier, loosen the guidelines. If you're more professional, tighten them. The key rule (punch up, never down) should stay.

## Example Usage

**You:** Atlassian just laid off 1,600 people to fund AI investments. Write a spicy take.

**Claude:** [Delivers a post that roasts the corporate framing while making a real observation about AI spending patterns]

**You:** Make it shorter.

**Claude:** [Compresses to the punchiest version]

## Works Well With

- **Hook Writer**: Generate hooks after the take is written
- **Tone Filter**: Final check before publishing
- **Post Writer**: Use the Post Writer for non-spicy content, this skill for the edgy stuff
