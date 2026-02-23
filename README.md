# vc-cold-emails

A Claude Code skill that writes cold emails to VCs. Not the garbage template kind. The kind that actually get replies.

Based on the [OpenVC top 1% cold email methodology](https://www.openvc.app/blog/how-to-cold-email-vc).

## Quick Start

**Step 1: Open Claude Code and paste these two lines (one at a time):**
```
/plugin marketplace add davidcoallier/vc-cold-email
```
```
/plugin install vc-cold-email@davidcoallier
```

**Step 2: Use it:**
```
/vc-cold-emails
```

Claude will ask you questions. Answer them. You get an email.

## What it does

You tell Claude you want to email a VC. Claude asks for the inputs it needs (investor name, why they're a fit, your traction signals, round size). Then it:

1. Runs pre-flight checks. If your signals are too weak or the investor's a bad fit, it tells you before you waste their time and yours.
2. Writes a subject line under 60 chars that fits a mobile notification and shows thesis fit.
3. Writes a body under 200 words. Personalised opening, one-liner, top 2-3 signals, clear ask, deck link.
4. Outputs the email with word count and a brief rationale.

No fluff. No "revolutionary" or "game-changing". Just the email.

## Why this exists

Most cold emails to VCs are bad. Too long, too generic, no signal, wrong investor. VCs get hundreds per week. They skim for 5 seconds and archive.

OpenVC analysed the top 1% of cold emails on their platform. This skill encodes those rules into a repeatable process.

## Installation

First, add the marketplace:
```
/plugin marketplace add davidcoallier/vc-cold-email
```

Then install the plugin:
```
/plugin install vc-cold-email@davidcoallier
```

### Local install from repo

```bash
git clone https://github.com/davidcoallier/vc-cold-email.git
cp -r vc-cold-email/skills/vc-cold-email ~/.claude/skills/vc-cold-email
```

### Verify it's working

Restart Claude Code, then run:
```
/vc-cold-emails
```

Claude should prompt you for investor and company details. If it doesn't, check that the skill folder is in `~/.claude/skills/` and that Code Execution is enabled in your settings.


## Basic Usage

```
/vc-cold-emails
```

Claude will ask for:
- Investor first name + firm
- Why this investor is a fit (portfolio, thesis, geography)
- Your company one-liner
- Your top 2-3 traction signals (specific numbers only)
- Funding stage + round size

If you don't have a strong signal (40%+ MoM growth, notable exits, committed lead, real IP), the skill will tell you cold outreach is premature. That's a feature, not a bug.

## How I use it

1. Open Claude Code
2. Drag your pitch deck (PDF) into the chat
3. Run:
```
/vc-cold-emails - use my deck for context
```

Claude will extract your traction signals, company description, and round details directly from the deck — no manual copy-paste needed.

## What counts as a strong signal

- Traction: revenue, volume, retention, growth rate with real numbers
- Team: previously exited founder, world-class domain expert
- Round signal: lead investor already committed
- IP/moat: patents, proprietary dataset, regulatory advantage

What doesn't count:
- Prototype
- Waitlist
- "Strong product vision"

## Files

- `SKILL.md` - The full skill definition Claude Code reads
- `templates/email.md` - Master template and Manano-specific copy blocks
- `templates/examples.md` - Real cold emails that worked, from OpenVC

## Credits

Methodology from [OpenVC](https://www.openvc.app/blog/how-to-cold-email-vc). They maintain a database of 6,000+ early-stage investors and have seen what actually gets replies.
