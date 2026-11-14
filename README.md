# reuse-before-research

Check existing work before starting new research, then make useful findings easy to find.

This skill helps an agent check existing skills, notes, files and earlier handovers before researching, refresh changeable evidence, and record useful findings.

## Install

Install with a compatible agent-skills tool:

```bash
npx skills add felipepetersmann22-star/reuse-before-research-skill
```

Alternatively, copy this repository into your agent’s skills directory, keeping `SKILL.md` and any supporting files together. Review the instructions and configure permissions and schedules for your own setup before use.

## Try it

Ask: "Compare the current prices for these services. Reuse my previous comparison, but verify anything that may have changed."

The skill uses prior work as context, checks relevant current sources and identifies anything it could not verify. It does not create notes, skills or archives unless the task or an existing workflow authorizes that work. A prior note alone is not evidence of a current price.

## Source and license

This standalone repository was separated from the public [agent-skills collection](https://github.com/felipepetersmann22-star/agent-skills/tree/1b7a3d8867363c0ff0dda0f9a117aacb7a16a347/skills/reuse-before-research).

MIT. See [LICENSE](LICENSE) and [CREDITS.md](CREDITS.md).
