# Pitch Anything — Claude Code Skills

Three skills for [Claude Code](https://claude.ai/code) based on [*Pitch Anything*](https://www.amazon.com/Pitch-Anything-Innovative-Presenting-Persuading/dp/0071752854) by Oren Klaff. 

## What You Get

**pitch-builder** — Build a complete 20-minute pitch from scratch. Walks you through the four-phase structure: big idea intro, tension loops, the deal, and hot cognition stacking. Outputs a timed script you can rehearse from.

**frame-control** — Real-time tactical advice for meetings, negotiations, and high-stakes conversations. Identifies the frame you're facing (power, time, analyst) and gives you specific counter-moves with scripts you can say out loud.

**pitch-review** — Paste any pitch, proposal, email, or sales message and get it audited against five layers: neediness, frame ownership, tension, hot/cold cognition balance, and structural timing. Returns a scored breakdown with concrete rewrites.

## Install

### Step 1: Download this repo

Click the green **Code** button at the top of this page, then **Download ZIP**. Unzip it somewhere you'll remember (like your Desktop or Downloads folder).

Or if you're comfortable with the terminal:

```
git clone https://github.com/YOUR_USERNAME/pitch-anything.git
```

### Step 2: Copy the skills into Claude Code

Open your terminal (on Mac: search for "Terminal" in Spotlight) and paste these three commands one at a time. Replace `~/Downloads/pitch-anything` with wherever you unzipped/cloned the repo:

```
cp -r ~/Downloads/pitch-anything/pitch-builder ~/.claude/skills/
cp -r ~/Downloads/pitch-anything/frame-control ~/.claude/skills/
cp -r ~/Downloads/pitch-anything/pitch-review ~/.claude/skills/
```

> **What this does:** It copies each skill folder into `~/.claude/skills/`, which is where Claude Code looks for skills. The `~` means your home folder.

### Step 3: Restart Claude Code

Quit Claude Code and reopen it. The skills will be picked up automatically — no settings to change.

## How to Use

Just talk to Claude naturally. The skills kick in automatically when you ask about pitches, negotiations, or persuasive writing. Some examples:

- *"Help me build a pitch for my Series A"*
- *"I'm going into a meeting with a tough investor — how do I handle pushback?"*
- *"Review this email and make it less needy"*
- *"Audit my proposal and tell me where I'm losing the frame"*
- *"I'm being steamrolled in negotiations — what do I do?"*

## Credit

These skills are based on frameworks from Pitch Anything by Oren Klaff. The underlying methodology is his work. This repo packages those concepts into a skill format for use with Claude. Buy the book, it's worth a read.
