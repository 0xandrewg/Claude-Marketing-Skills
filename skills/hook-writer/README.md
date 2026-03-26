# Hook Writer

Generates 10 hook options across 5 proven techniques for any LinkedIn post. The hook is the first 2 lines before "... more" and it's the single biggest factor in whether anyone reads your post.

## What It Does

- Takes any finished post and generates 10 hooks (2 per technique)
- Each hook is exactly 2 lines, optimized for LinkedIn's "... more" cutoff (~55 characters per line)
- Covers 5 techniques: Contradiction, Specific Number, Direct Accusation, Stolen Thought, Absurd Reframe
- Every hook creates an open loop that forces the click

## How to Load It

1. Create a new Claude Project (or add to an existing one)
2. Go to Project Knowledge > Add content
3. Copy the entire contents of `SKILL.md` and paste it in

## How to Customize

### Add your own techniques
The 5 techniques cover most hook styles, but if you've found something that works for your audience, add it as technique #6 with 2-3 examples.

### Weight toward favorites
If Stolen Thought hooks consistently outperform for you, tell Claude: "Give me 4 Stolen Thought hooks and 2 of each other technique." The skill adapts.

### Adjust character count
The default is ~55 characters per line. If your audience reads on desktop more than mobile, you can extend this to ~70 characters.

## Example Usage

**You:** [paste your finished post] Write hooks for this.

**Claude:** [Returns 10 hooks organized by technique]

**You:** I like #3 and #7. Combine elements from both.

**Claude:** [Returns refined hybrid hook]

## Works Well With

- **Post Writer**: Write the post first, then generate hooks
- **Tone Filter**: Make sure the hook passes the avoid list too
