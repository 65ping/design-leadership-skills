# Design Leadership Skill for Claude Code

A **Claude Code skill** that turns Claude into a senior advisor for design org leadership and organizational decisions. Built for **VP of Design**, **Head of Design**, **Design Leads** and **CPO** navigating the real, hard calls that don't have easy answers.

Ask it anything about org structure, hiring, managing up, team culture, vision-setting, performance management, or growing as a design executive - and get framework-grounded, opinionated guidance.

---

## Install

### Option A - Claude Code CLI (recommended)

```bash
claude skill install gh:65ping/design-leadership-skill
```

### Option B - Manual

```bash
mkdir -p ~/.claude/skills/design-leadership
curl -o ~/.claude/skills/design-leadership/SKILL.md \
  https://raw.githubusercontent.com/65ping/design-leadership-skill/main/SKILL.md
```

Then restart Claude Code. The skill activates automatically when relevant.

---

## What It Covers

Nine decision domains, each with named frameworks, decision matrices, and anti-patterns:

| Domain | Example Questions |
|---|---|
| **Org Structure & Team Models** | Should I centralize or embed designers? What stage is my org at? |
| **Hiring & Building the Team** | What do I look for in a design manager? Should I promote or hire externally? |
| **Managing Up & Stakeholder Influence** | How do I get a seat at the table? How do I talk to the CEO about design? |
| **Cross-Functional Relationships** | How do I fix the design–product–engineering triangle? |
| **Vision, Strategy & Direction-Setting** | How do I set a design vision that actually lands? How do I measure design? |
| **Performance & People Management** | How do I handle an underperformer? What makes a 1:1 actually useful? |
| **Culture & Ways of Working** | How do I build a critique culture? What rituals matter most? |
| **Team Scaling & Growth** | When do I need more headcount? How do I delegate as I grow? |
| **Self-Management for Senior Leaders** | How do I make the Director → VP transition? How do I manage imposter syndrome? |

---

## Key Frameworks Included

- **Centralized / Embedded / Federated** org models with when-to-use criteria
- **5 Design Org Maturity Stages** - diagnose where you are and what the next stage requires
- **12 Qualities of Effective Design Orgs** - foundation, output, and management dimensions
- **Three-Legged Stool** - business, technology, and design as peer capabilities
- **Double Diamond as Executive Tool** - how to push design upstream into strategy
- **Future Org Chart Exercise** - hiring 18 months ahead, not for today
- **Feedback Stack** - three layers of performance feedback, all required
- **Critique Principles** - describe before you prescribe, ask don't tell
- **Span of Control Guidelines** - 5–8 ICs, 3–5 managers, and why it matters
- **Quick Decision Reference Table** - 13 common leadership questions mapped to the right framework

---

## How to Use

Once installed, just ask Claude naturally:

> "How should I structure my design team now that we're scaling to 40 designers?"

> "I have a senior designer who's underperforming - how do I handle this?"

> "What does it take to go from Director to VP of Design?"

> "How do I build a design critique culture that actually sticks?"

The skill activates automatically on design leadership questions. No slash command needed, though you can also invoke it directly with `/design-leadership`.

---

## Who This Is For

- **VP of Design / Head of Design** - org structure, exec presence, team scaling
- **CPO** - design–product partnership, roadmap, cross-functional dynamics
- **CTO** - design–engineering relationship, org design at scale
- **Design Directors** - preparing for VP transition, managing managers
- **Senior Design Managers** - building culture, growing as leaders

---

## Topics

`claude-skill` · `design-leadership` · `org-design` · `vp-design` · `design-management` · `claude-code` · `design-org` · `product-design` · `leadership-frameworks`
