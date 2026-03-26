# Claude Marketing Skills

A free, open source suite of Claude Project skills for content marketers, founders, and builders who want to stop fighting their AI tools and start shipping content that sounds like a human wrote it.

Each skill is a standalone instruction file you drop into a Claude Project. No code. No setup. Just copy the file, paste it into your project, and start using it.

## What's Inside

| Skill | What It Does |
|-------|-------------|
| **Post Writer** | Writes LinkedIn posts following a proven structure with built-in tone rules and an avoid list that kills corporate slop |
| **Hook Writer** | Generates 10 hook options across 5 techniques for any post (the first 2 lines before "... more" on LinkedIn) |
| **Spicy Take Generator** | Takes a news story or topic and wraps real insight inside humor, internet culture, and contrarian framing |
| **Content Calendar** | Builds weekly content plans organized around 4 content pillars with specific formats and example hooks for each day |
| **Tone Filter** | Scans any draft and catches corporate filler, AI slop, hype language, and formatting problems before you publish |

## Quick Start

1. Open [Claude](https://claude.ai) and create a new Project
2. Go to **Project Knowledge** and click **Add content**
3. Copy the contents of any `SKILL.md` file and paste it in
4. Start chatting with Claude inside that Project

That's it. The skill is active for every conversation in that Project.

## Loading Multiple Skills

You can load multiple skills into the same Project. They work together. For example, loading the Post Writer + Hook Writer + Tone Filter gives you a full content pipeline:

1. Write the post (Post Writer handles structure and tone)
2. Generate hooks (Hook Writer gives you 10 options)
3. Run the final draft through the Tone Filter before publishing

## Customizing for Your Voice

Every skill has a README explaining what to customize. The most common changes:

- **Tone**: Each skill has a voice/tone section. Replace the examples with your own writing samples.
- **Avoid list**: The Tone Filter has a comprehensive avoid list. Add or remove terms based on your brand.
- **Content pillars**: The Content Calendar skill uses 4 default pillars. Swap them for your own.
- **Hook techniques**: The Hook Writer uses 5 techniques. You can weight them toward your favorites.

## Who This Is For

- Content marketers tired of AI-generated posts that sound like every other AI-generated post
- Founders building a personal brand on LinkedIn
- Builders who want to document their work publicly without sounding corporate
- Anyone who's ever read their own AI-written post and thought "this sounds like a robot having a meeting"

## Skills Overview

### Post Writer (`skills/post-writer/SKILL.md`)
The core skill. Handles post structure, tone, formatting rules, and runs every draft against the avoid list. Supports multiple content pillars and formats.

### Hook Writer (`skills/hook-writer/SKILL.md`)
Generates 10 hook options across 5 proven techniques: Contradiction, Specific Number + Unexpected Context, Direct Accusation, Stolen Thought, and Absurd Reframe. Each hook is exactly 2 lines, optimized for the LinkedIn "... more" cutoff.

### Spicy Take Generator (`skills/spicy-take-generator/SKILL.md`)
Takes a news story, trend, or topic and produces contrarian, humorous posts with real insight underneath. Follows the 60/40 rule: fun wrapper, real substance underneath. Built for the Timeline Roast and Spicy Takes content pillars.

### Content Calendar (`skills/content-calendar/SKILL.md`)
Builds weekly content plans based on 4 pillars: Build Log, Timeline Roast, Spicy Takes, and Builder's Journal. Assigns formats, suggests topics from current events, and balances the weekly mix.

### Tone Filter (`skills/tone-filter/SKILL.md`)
The quality control layer. Scans any draft and flags: AI hype language, corporate filler, generic marketing phrasing, vague outcomes, formatting slop, and strategic red flags. Returns a clean version with specific fixes.

## Contributing

Found a phrase that should be on the avoid list? Built a new skill that fits the suite? Open a PR.

## License

MIT. Use it however you want. Credit appreciated but not required.
