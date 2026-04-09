# willify

A collection of custom Claude Code skills.

## Skills

### `iterate`

Iterates on a prototype by distilling it into a minimal behavioral spec, then reimplementing from scratch via a contextless subagent. Sheds implementation baggage without losing intent.

**Use when:** "reimplement my prototype", "clean-room rewrite", "spec out what this does and redo it"

**Process:**
1. Reads the prototype
2. Extracts a minimal behavioral spec (what, not how)
3. Optionally resets to merge-base to enforce clean-room
4. Relaunches a subagent with only the spec to reimplement from scratch

## Installation

```sh
npx skills add willregelmann/willify
```
