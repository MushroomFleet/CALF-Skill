# CALF — Character Authenticity Language Framework
### A Claude AI Skill for Narrative & Character Design Assessment

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub](https://img.shields.io/badge/GitHub-CALF--Skill-blue?logo=github)](https://github.com/MushroomFleet/CALF-Skill)

CALF WEB: [https://scuffedepoch.com/calf/](https://scuffedepoch.com/calf/)
SUBSTACK: [why-characters-die-and-what-the-numbers](https://mushroomfleet.substack.com/p/why-characters-die-and-what-the-numbers)

---

## What is CALF?

CALF is an advisory Claude skill that assesses and enhances creative plans using the principles of the **Character Authenticity Language Framework** — a structural, psychologically grounded diagnostic for why characters work, and why they stop working.

It operates as a narrative design consultant: analytically rigorous, emotionally intelligent, and commercially grounded. CALF doesn't engage in ideological critique. Every argument it makes is **structural**: this element performs this function; removing it without replacement causes this specific failure mode.

The framework draws on archetypal psychology, the 78-card tarot deck as a character mapping system, and a documented pattern of commercial failures traceable to the same root causes — character elements removed without functional replacement, contemporary norms imported into worlds that haven't earned them, aspirational geometry collapsed without a replacement anchor.

---

## What CALF Assesses

Submit any markdown plan — a game design document, character bible, narrative outline, franchise roadmap, adaptation brief, or story plan — and CALF runs a structured diagnostic across **five core dimensions**:

| # | Dimension | Core Question |
|---|-----------|--------------|
| 1 | **Archetypal Resonance** | Does each character map to a consistent, legible archetypal energy across their arc? |
| 2 | **Narrative Coherence** | Do the character's "problems" serve load-bearing narrative functions? |
| 3 | **World Coherence** | Does every character arc operate within the actual rules of the world they inhabit? |
| 4 | **Aspirational Architecture** | Is the aspirational geometry intact — does the audience have somewhere to aim? |
| 5 | **Context Integrity** | Are aesthetic and physical elements coherent with the world and narrative context? |

Each dimension scores **0–20** for a maximum of **100 points**, with a full commercial risk assessment and priority recommendation list.

---

## What CALF Produces

For every submitted plan, CALF outputs a `[projectname]_README_CALF.md` containing:

- **Tarot Continuity Map** — each significant character's primary archetypal card at each narrative phase, with continuity verdict
- **Load-Bearing Element Audit** — every structural "problem" the characters carry, what it enables, and what breaks if it's removed
- **World Coherence Report** — flags any contemporary norms imported into historically or culturally specific worlds
- **Aspirational Architecture Report** — identifies aspirational vacuums where idealization has been collapsed
- **Scored Assessment** across all five dimensions
- **Active Flags** — 🔴 REPLACEMENT, 🟠 LOAD-BEARING REMOVAL, 🟡 WORLD RUPTURE, 🟡 ASPIRATIONAL VACUUM, 🔵 CONTEXT MISMATCH
- **Enhanced Plan** — the original document with CALF-aligned revisions embedded as `> [CALF]` blockquotes for full traceability

---

## Skill Contents

```
calf/
├── SKILL.md                    ← Main skill: workflow, dimensions, diagnostic flags, agent tone
└── references/
    ├── FRAMEWORK.md            ← Full theoretical grounding document
    ├── TAROT_ARCHETYPES.md     ← Complete 78-card reference for character arc mapping
    ├── REPORT_TEMPLATE.md      ← Structured output template for all assessments
    └── CASE_STUDIES.md         ← Annotated cases: Luke Skywalker, Art3mis, Will Byers, Baywatch
```

The **tarot reference** provides a full 78-card psychological mapping system — upright and reversed polarities, archetypal families, and arc continuity rules — used to detect when a character has been *replaced* rather than *evolved*.

The **case studies** walk through four canonical examples in full CALF notation:
- Luke Skywalker (Original Trilogy vs. Disney Sequels) — Archetypal Replacement
- Art3mis (Ready Player One novel vs. film) — Load-Bearing Element Removal
- Will Byers (Stranger Things) — World Coherence Failure
- Baywatch — Context as Evaluation Framework (retroactive misreading corrected)

---

## How to Install

### Option 1 — Install the `.skill` file directly

Download [`calf.skill`](https://github.com/MushroomFleet/CALF-Skill/releases) from the releases page.

The `.skill` format is a standard **ZIP archive** with a `.skill` extension. You can inspect its contents at any time by renaming it to `.zip` and opening it with any archive manager, or by running:

```bash
unzip -l calf.skill
```

To extract and browse the full skill contents:

```bash
unzip calf.skill -d calf-unpacked/
```

Once downloaded, install it into your Claude skills directory according to your Claude environment's skill installation instructions.

### Option 2 — Clone and use directly

```bash
git clone https://github.com/MushroomFleet/CALF-Skill.git
```

Point your Claude environment's skill path at the `calf/` directory inside the repo.

---

## How to Trigger CALF

CALF activates when you submit a markdown document alongside any of the following trigger phrases:

| Trigger | Use Case |
|---------|----------|
| `using CALF` | Explicit invocation |
| `CALF review` | Assessment request |
| `character authenticity assessment` | Full diagnostic |
| `why does this character feel wrong` | Diagnostic on a specific problem |
| `narrative coherence check` | World/arc coherence focus |
| `character redesign audit` | Reboot or adaptation review |
| `assess my characters` | Roster-level assessment |

You can also simply upload or paste a GDD, character bible, script outline, or story plan and ask for an **authenticity review**, **commercial viability check**, or **archetypal assessment** — CALF will recognise the context and engage.

---

## Example Usage

```
Here's my game design document. I want a CALF review — specifically I'm worried 
the protagonist's arc in Act 3 feels disconnected from who she was in Act 1. 
Can you run the tarot continuity check and load-bearing audit?

[paste your markdown GDD]
```

```
using CALF — this is a character bible for a historical drama set in 1970s 
New York. Please assess world coherence and flag any contemporary norms 
that the world hasn't earned.

[paste your markdown character bible]
```

---

## When CALF Is Most Valuable

- **Adaptations and reboots** — before finalising changes to established characters
- **Sequels** — verifying character arc continuity across installments
- **Historical settings** — checking that sensitive identity arcs operate within the world's actual rules
- **Role model characters** — ensuring aspirational geometry is preserved when representational goals are added
- **Character redesigns** — auditing what is load-bearing before anything is changed
- **Franchise development** — assessing the full ensemble's archetypal health

---

## The Framework in Brief

The Character Authenticity Framework rests on a single structural insight:

> Characters either work or they don't. The reasons they stop working are almost always the same.

Successful characters are solutions to a multi-variable equation: psychological resonance, narrative function, cultural context, aspirational geometry, and contextual coherence. These variables operate as a **system**. Alter one without compensating elsewhere and cascading failures follow.

The market reflects this at an instinctive level. Audiences do not need to be able to name the problem. They feel it immediately. CALF provides the analytical language to name what audiences feel — so that creative decisions can be made with full awareness of what is structurally at stake.

---

## Diagnostic Flags Quick Reference

| Flag | Meaning |
|------|---------|
| 🔴 REPLACEMENT | Character's archetypal core changed without a legible bridge |
| 🟠 LOAD-BEARING REMOVAL | Structural element removed without functional replacement |
| 🟡 WORLD RUPTURE | Arc imports norms the world has not earned |
| 🟡 ASPIRATIONAL VACUUM | Aspirational function removed; no replacement identified |
| 🔵 CONTEXT MISMATCH | Aesthetic element altered without world-coherent justification |
| ✅ AUTHENTIC | Element is coherent, functional, and archetypal sound |

---

## 📚 Citation

### Academic Citation

If you use this skill or framework in your research or project, please cite:

```bibtex
@software{calf_skill,
  title = {CALF: Character Authenticity Language Framework Skill for Claude AI},
  author = {Drift Johnson},
  year = {2025},
  url = {https://github.com/MushroomFleet/CALF-Skill},
  version = {1.0.0}
}
```

### Donate

[![Ko-Fi](https://cdn.ko-fi.com/cdn/kofi3.png?v=3)](https://ko-fi.com/driftjohnson)
