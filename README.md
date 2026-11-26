# review-game-art

An engine-agnostic skill for designing and reviewing game art. It covers 2D concept approval before modeling, concept-to-texture comparison, organic and mechanical motion, staged construction, and in-game visual review.

## Install with npx

Install for Codex and Claude Code across your projects.

```sh
npx skills add kmaida/review-game-art --skill review-game-art -g -a codex -a claude-code
```

To install for one game, run this from that game's repository root.

```sh
npx skills add kmaida/review-game-art --skill review-game-art -a codex -a claude-code
```

Target one client by keeping its `-a` flag. See the [skills CLI reference](https://github.com/vercel-labs/skills/blob/main/docs/commands.md) for more installation options.

## Use

Ask your agent to use `review-game-art` when designing or reviewing a visual asset. You can also invoke `$review-game-art` in Codex or `/review-game-art` in Claude Code. For a new 3D asset, use the skill to review the final 2D concept for every required gameplay state before starting a mesh or blockout.
