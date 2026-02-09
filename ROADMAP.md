ROADMAP.md
# AntiTrend Roadmap

AntiTrend helps people block fast-fashion and non-ethical shopping — on their terms.
This roadmap is intentionally lean to keep v1 calm, useful, and shippable.

## Product principles (guardrails)
- User-controlled > algorithm-controlled
- Quiet by default (minimal prompts/notifications)
- No shame, no moral scoring
- Simple v1: one core job, done well

---

## v0: Definition + scaffolding (now)
**Goal:** Make the product buildable without expanding scope.

- [ ] Define the single core action (“The main thing a user does is ___”)
- [ ] Confirm platform approach for v1 (choose one):
  - [ ] Mobile app only (manual list + share sheet)
  - [ ] Browser extension only (blocklist/allowlist)
  - [ ] Hybrid later (not now)
- [ ] Create initial data model:
  - [ ] Brand
  - [ ] Retailer / domain
  - [ ] Category tags (fast-fashion, labor, materials, etc.)
  - [ ] User rules (block/allow/exception)
- [ ] Set up repo basics (README, CONTRIBUTING, ISSUE templates)

Deliverable: a one-page Product Brief + repo structure.

---

## v1: MVP (Block + Control) ✅
**Goal:** A user can set boundaries and the app enforces them.

### Onboarding + Rules
- [ ] Create “values / boundaries” onboarding (short, skippable)
- [ ] Rule types:
  - [ ] Block brand
  - [ ] Block retailer/domain
  - [ ] Allow exceptions (whitelist)
- [ ] Import/export rules (basic JSON or simple file)

### Blocking behavior
- [ ] Clear definition of “blocked” experience:
  - [ ] Hide results
  - [ ] Warn + require confirm
  - [ ] Hard block (if supported by platform)
- [ ] Minimal, calm UX copy (“This is blocked by your rules”)

### Transparency
- [ ] “Why am I seeing this?” (shows the rule that triggered)
- [ ] Activity log (optional, private)

Deliverable: working MVP that enforces user-defined rules.

---

## v1.1: Usability + trust
**Goal:** Make it feel effortless and reliable.

- [ ] Search + manage blocklist (fast)
- [ ] Bulk add (paste list of brands/domains)
- [ ] Suggested starter packs (optional):
  - [ ] Fast-fashion starter list
  - [ ] “My personal triggers” pack
- [ ] Backup/sync (if accounts exist) OR local export reminder

Deliverable: users can maintain their rules without friction.

---

## v2: Intelligence (only after trust)
**Goal:** Help users discover what to block—without taking control.

- [ ] “Looks like fast-fashion?” detection (flag, don’t auto-block)
- [ ] Evidence panel (sources + links, no moral score)
- [ ] Alternatives (only if user opts in)

Deliverable: opt-in guidance that respects autonomy.

---

## v3: Expansion
- [ ] Community packs (curated, not chaotic)
- [ ] Category-level rules (materials, labor, etc.)
- [ ] Multi-platform parity (mobile + extension)

---

## Non-goals (not in v1)
- Social feed / sharing / followers
- Public profiles
- Gamification / points / streaks
- Moral “scores” or shaming language
- Constant push notifications

