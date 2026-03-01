# Pitch Anything — Claude Code Skills

Three Claude Code skills based on [*Pitch Anything*](https://www.amazon.com/Pitch-Anything-Innovative-Presenting-Persuading/dp/0071752854) by Oren Klaff. Build pitches, control frames, and audit your messaging — all inside Claude Code.

## Skills

### `/pitch-builder`
Build a complete 20-minute pitch from scratch. Walks you through the four-phase structure: big idea intro, tension loops, the deal, and hot cognition stacking. Outputs a timed script you can rehearse from.

### `/frame-control`
Real-time tactical advice for meetings, negotiations, and high-stakes conversations. Identifies the frame you're facing (power, time, analyst) and gives you specific counter-moves with scripts you can say out loud.

### `/pitch-review`
Paste any pitch, proposal, email, or sales message and get it audited against five layers: neediness, frame ownership, tension, hot/cold cognition balance, and structural timing. Returns a scored breakdown with concrete rewrites.

## Install

Clone the repo, then copy or symlink the skill folders into your Claude Code skills directory.

**Personal install** (available in all your projects):

```bash
# Clone
git clone https://github.com/YOUR_USERNAME/pitch-anything.git

# Copy skills
cp -r pitch-anything/pitch-builder ~/.claude/skills/
cp -r pitch-anything/frame-control ~/.claude/skills/
cp -r pitch-anything/pitch-review ~/.claude/skills/
```

**Project install** (available only in one project):

```bash
cp -r pitch-anything/pitch-builder .claude/skills/
cp -r pitch-anything/frame-control .claude/skills/
cp -r pitch-anything/pitch-review .claude/skills/
```

Restart Claude Code after installing. The skills are auto-discovered — no settings changes needed.

## Usage

The skills trigger automatically when you ask Claude to help with pitches, negotiations, or persuasive writing. You can also invoke them directly:

- *"Help me build a pitch for my Series A"*
- *"I have a meeting with a difficult client tomorrow — how do I handle pushback?"*
- *"Review this email and make it less needy"*
- *"Audit my investor deck narrative"*

## What's Inside

```
pitch-builder/
├── SKILL.md
└── references/
    ├── frame-control-tactics.md
    └── tension-patterns.md

frame-control/
├── SKILL.md
└── references/
    └── scenario-playbook.md

pitch-review/
├── SKILL.md
└── references/
    ├── anti-patterns.md
    └── hot-cold-scoring.md
```

## Credit

Framework and methodology from [*Pitch Anything*](https://www.amazon.com/Pitch-Anything-Innovative-Presenting-Persuading/dp/0071752854) by Oren Klaff.
