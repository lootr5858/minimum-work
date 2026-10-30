# Minimum Work

A portable skill for completing the requested outcome with the least sufficient investigation, process, changes, and validation. Adapted from MSW for personal use across Codex and Claude Code.

The canonical instructions are [skills/minimum-work/SKILL.md](skills/minimum-work/SKILL.md). The skill is self-contained and may also be invoked explicitly as `$minimum-work` in Codex or `/minimum-work` in Claude Code. Reading the skill through another route does not prove that its hooks ran.

The plugin includes hooks that load the skill at session and subagent start. Hook commands require `cat` and Python 3.

## Attribution

Adapted from **MSW (Minimum Sufficient Work)** by **Slopware Engineer (@aienginerd)**, from [transcendr/slopware-skills](https://github.com/transcendr/slopware-skills).

Upstream base: [`bb6048c8b022e73eef599d7e0ecb9bdf1a8b6d8a`](https://github.com/transcendr/slopware-skills/blob/bb6048c8b022e73eef599d7e0ecb9bdf1a8b6d8a/plugins/msw/skills/msw/SKILL.md).

Changes: proportional process without mandatory visible contract ceremony; a necessity test that permits investigation of concrete uncertainty; routine autonomy; scalable procedural defaults; bounded change scope; sufficient validation without automatic repeated review; honest blocked reporting without an arbitrary round fuse; concise reporting; and full-skill session/subagent delivery.

Copyright (c) 2026 Slopware Engineer. Adaptation copyright (c) 2026 Evan. Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/); see [LICENSE](LICENSE) for preserved upstream notices. No warranties are given. This adaptation is not endorsed by the upstream author.
