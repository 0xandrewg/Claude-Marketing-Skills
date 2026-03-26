# Post Writer

The core skill in the suite. Handles post structure, tone, formatting, and runs every draft against a comprehensive avoid list that kills corporate AI slop.

## What It Does

- Writes LinkedIn posts in a human voice with builder/experimenter energy
- Applies the 60/40 rule: personality wrapper, real insight underneath
- Maps every post to one of four content pillars (Build Log, Timeline Roast, Spicy Takes, Builder's Journal)
- Scans every draft against a master avoid list of 80+ banned phrases
- Formats for mobile (short paragraphs, no em dashes, minimal emoji)

## How to Load It

1. Create a new Claude Project (or open an existing one)
2. Go to Project Knowledge > Add content
3. Copy the entire contents of `SKILL.md` and paste it in
4. Start writing

## How to Customize

### Change the voice
The "Voice and Tone" section has "Never Sound Like This" and "Always Sound Like This" examples. Replace these with your own examples. Pull 3-5 sentences from posts you've written that sound most like you.

### Change the content pillars
The default pillars are Build Log, Timeline Roast, Spicy Takes, and Builder's Journal. Swap these for whatever categories your content falls into. Keep it to 3-5 pillars.

### Add to the avoid list
The avoid list covers most corporate and AI slop, but you probably have pet peeves specific to your industry. Add them to the relevant category.

### Change the formatting rules
The default rules ban em dashes and limit emoji. If that's not your style, adjust. The important thing is having rules at all so the output is consistent.

## Example Usage

**You:** Write me a Build Log post about an automation I built this weekend that scrapes competitor pricing and sends me a daily email digest. It took 4 hours to build and saves me about 30 minutes a day.

**Claude:** [Delivers a post in your voice, following the structure, with the avoid list applied]

## Works Well With

- **Hook Writer**: Write the post first, then generate hooks
- **Tone Filter**: Run the final draft through the filter before publishing
