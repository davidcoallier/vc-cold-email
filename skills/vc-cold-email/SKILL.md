---
name: vc-cold-email
description: Write cold emails to VC investors that get replies. Use when the user wants to draft, write, or improve an outreach email to a venture capital investor, angel investor, or fundraising prospect. Covers subject lines, email body, traction signals, personalisation, and investor targeting. Based on the OpenVC top 1% cold email methodology.
---

# VC Cold Email

Write cold emails to VC investors that get replies, following the OpenVC top 1% methodology.

## How this Skill works

1. Gather context (see Inputs below)
2. Run pre-flight checks — abort early if signals are too weak
3. Draft subject line and body following the rules
4. Output the email with word count, character count, and a brief rationale

For the master template and Manano-specific copy blocks, see [templates/email.md](templates/email.md).
For real worked examples, see [templates/examples.md](templates/examples.md).

---

## Inputs to collect

Before writing, confirm you have all of these:

| Input | How to get it |
|---|---|
| Investor first name + firm | Ask the user |
| Why this investor is a fit | Ask the user, or research their portfolio/thesis |
| Company one-liner | Ask the user |
| Top 2–3 traction signals | Ask the user |
| Funding stage + round size | Ask the user |

If any are missing, ask. Do not guess or invent signals.

---

## Pre-flight checks

Run before writing anything. If Check 1 fails, stop and advise the user.

### Check 1 — At least one strong signal?

Strong signals (need at least one):
- **Traction**: 40%+ MoM growth, significant revenue, strong retention, GMV milestone
- **Team**: previously exited founder, world-class domain expert
- **Round signal**: lead investor already committed
- **IP/moat**: patents, proprietary dataset, regulatory advantage

NOT enough on their own:
- Prototype or MVP
- Waitlist
- "Strong product vision"

If no strong signal → cold outreach is premature. Recommend angels or accelerators instead. Say this clearly.

### Check 2 — Right investor?

Verify all four before writing:
- **Thesis fit**: does this VC invest in this sector?
- **Stage fit**: do they invest at this stage?
- **Geography fit**: do they invest in this region?
- **Check size fit**: does the round size match their typical cheque?

If any fail → flag it and do not write the email.

### Check 3 — Right person at the firm?

Identify the partner or principal whose portfolio aligns with the sector. Avoid `info@` or `contact@` unless genuinely no other option exists.

---

## Subject line rules

The subject line determines whether the email gets opened. Must fit a mobile notification.

**Formula**: `[Company] | [thesis fit signal] | [traction/team signal] · [stage]`

**6 rules — all must be followed:**
1. Under 60 characters — readable in full on a phone notification
2. No "investment opportunity" or "investment idea" — wasted space, zero signal
3. Include thesis fit — e.g. "WhatsApp fintech for trades" for a fintech VC
4. Include one proof of greatness — growth stat, team signal, or lead committed
5. Include funding stage — confirms fit and states intent
6. Include company name — useful for later inbox search (optional but good)

**Good:**
```
Manano | WhatsApp fintech for trades | €9M vol · Seed
2x exited founder | B2B SaaS payments | Pre-Series A
40% MoM growth | FinOps for SMEs | Seed round
```

**Bad:**
```
Investment opportunity in fintech    ← generic, wastes space
Looking for funding                  ← no value signal
Exciting new startup                 ← meaningless
```

---

## Email body rules

**Target: 150 words. Hard maximum: 200 words.** If longer, cut it.

### Structure (in this order):

**1. Personalised opening (1–2 sentences)**
Use the investor's first name. Include a genuine hook based on their portfolio, stated thesis, or a public statement — not a generic compliment. If unable to personalise, ask the user for more investor context.

**2. Company intro (1 sentence)**
What the company does and for whom. Plain language — a non-expert must understand it instantly. No jargon.

**3. Top signals (2–3 sentences)**
Lead with the strongest metric. Be specific — exact numbers only. Pick the best 2–3 signals maximum.

**4. The ask (2–3 sentences)**
State funding stage and round size. Mention lead or notable angels if committed. One CTA only: a 20-minute call.

**5. Close**
Trackable deck link. Name, title, company, phone/email.

### 15-point checklist before delivering:

- [ ] Investor's first name used
- [ ] Personalised hook is specific, not generic
- [ ] One-liner clearly explains what the company does
- [ ] Target market is named
- [ ] Strongest signal leads
- [ ] Numbers are exact (not "strong growth" — say "40% MoM")
- [ ] No more than 3 metrics listed
- [ ] Funding stage stated
- [ ] Round size stated
- [ ] Single CTA only (a call)
- [ ] Deck linked, not attached
- [ ] Contact info included
- [ ] Word count ≤ 200
- [ ] No bullet points inside the email (prose only)
- [ ] No marketing fluff ("game-changing", "revolutionary", "disruptive")

---

## Common mistakes — flag these if spotted

| Mistake | Why it fails |
|---|---|
| No personalisation / copy-paste | VCs talk to each other; ruins reputation |
| Leading with the problem, not traction | VCs see 1,000 problem slides; they back traction |
| Asking for a warm intro in first contact | Presumptuous; ask for a call first |
| Burying the ask | VCs skim; make the ask explicit and early |
| Attaching a PDF deck | Untrackable; always use a link |
| Subject line missing thesis fit | Irrelevance in 5 seconds = no open |
| Over 200 words | Signals unclear thinking |
| No strong signal | "Great product" is not a reason to meet |
| Adjectives without data | "Impressive traction" means nothing; "72% activation rate" does |

---

## Output format

Deliver in this order:

1. **Pre-flight result** — one line confirming investor fit and signal strength (or flagging issues)
2. **Subject line** — with `[X chars]` count
3. **Email body** — with `[X words]` count
4. **Rationale** — 2–3 sentences: which signal you led with and why, what the personalised hook is based on

---

## Process notes

- Start with lower-priority targets to refine before top-tier VCs
- 3–4 personalised emails per day beats 50 generic blasts
- One follow-up after 5–7 days if no reply — expected and acceptable
- Use a trackable deck link (Docsend, Pitch, or OpenVC) to monitor opens
