# Global Tasks

## Purpose
This file tracks reusable cross-initiative work only.

It does not replace initiative-level `tasks.md`.

Use this file to track:
- new reusable global patterns
- updates to global rules
- shared shell/family/view/component work
- reusable AI behavior updates
- reusable host-variant work
- system-level improvements that affect multiple initiatives

Do not use this file for initiative-only tasks.

Initiative-specific execution must stay in:
- `/docs/initiatives/<initiative-name>/tasks.md`

---

## Task Status Legend
- `not-started`
- `in-progress`
- `blocked`
- `done`
- `deferred`

## Task Type Legend
- `reuse`
- `tailor`
- `new-global`
- `maintenance`

---

## Current Global Task Rules

### Rule 1 — Reuse first
If a reusable element already exists and is sufficient, reuse it and do not recreate it.

### Rule 2 — Create globally if reusable
If an initiative needs something that should be reused later, create it in the correct global location first.

### Rule 3 — Keep initiative work separate
Do not move initiative-only tasks into this file.

### Rule 4 — Mark completion clearly
When a reusable item is complete, mark it as `done` so future initiatives can skip recreating it.

---

## Global Task Backlog

### G-001 — Refine product shell specification
- **status:** in-progress
- **type:** new-global
- **depends-on:** none
- **output:** `/docs/global/02_product-shell-extension.md`
- **purpose:** strengthen the reusable product-shell definition with clearer row anatomy, behavior, and future refinement points
- **notes:** current product header is based on Microsoft Power Apps OOB and currently uses known total height = 239px; row-level refinement may be added later

### G-002 — Tighten persona fidelity to source wording
- **status:** in-progress
- **type:** maintenance
- **depends-on:** `/docs/personas/*.md`
- **output:** `/docs/personas/pm.md`, `/docs/personas/program-manager.md`, `/docs/personas/portfolio-manager.md`
- **purpose:** keep persona markdown as close as possible to source wording while retaining structured markdown format
- **notes:** persona files are already structured, but may need stricter wording alignment

### G-003 — Refine Operational Overview family rules
- **status:** in-progress
- **type:** new-global
- **depends-on:** `/docs/global/03_operational-overview-family.md`
- **output:** `/docs/global/03_operational-overview-family.md`
- **purpose:** further strengthen the reusable overview family rules for landing-level, product/sub-level, desktop/tablet, and mobile variants
- **notes:** overview family is established, but future refinement is expected as more initiatives are added

### G-004 — Define mobile family variant rules
- **status:** not-started
- **type:** new-global
- **depends-on:** `/docs/families/operational-overview/mobile.md`
- **output:** mobile family variant guidance
- **purpose:** define how the same family purpose adapts on mobile using a different layout pattern when necessary
- **notes:** family purpose stays reusable even if mobile layout differs

### G-005 — Refine global view versioning model
- **status:** not-started
- **type:** new-global
- **depends-on:** `/docs/global/07_view-patterns.md`
- **output:** stronger versioning/reference logic for reusable views
- **purpose:** ensure reusable view patterns such as board/list/table can evolve centrally and be inherited consistently across initiatives

### G-006 — Refine component reference/versioning model
- **status:** not-started
- **type:** new-global
- **depends-on:** `/docs/global/06_visualization-rules.md`
- **output:** stronger reusable component reference/versioning guidance
- **purpose:** ensure reusable components can be improved globally and referenced consistently by initiatives

### G-007 — Define Teams host-shell behavior
- **status:** not-started
- **type:** new-global
- **depends-on:** `/docs/global/08_host-shell-variants.md`
- **output:** Teams host-shell rules
- **purpose:** define how Ask Altus, shell placement, and canvas behavior adapt in Teams without breaking family consistency

---

## Completed Global Tasks

### G-000 — Establish reusable global file structure
- **status:** done
- **type:** new-global
- **depends-on:** none
- **output:** `/docs/global/00_design-system.md` to `/docs/global/08_host-shell-variants.md`
- **purpose:** establish the reusable global source-of-truth file system

### G-000a — Establish persona source-of-truth structure
- **status:** done
- **type:** new-global
- **depends-on:** none
- **output:** `/docs/personas/*.md`
- **purpose:** establish persona files as separate reusable source files referenced by the persona-model framework

### G-000b — Establish reusable initiative structure
- **status:** done
- **type:** new-global
- **depends-on:** none
- **output:** `/docs/initiatives/<initiative-name>/...`
- **purpose:** establish a reusable initiative-level structure for masterplan, tasks, app flow, and implementation files

---

## How to Use This File

When a new initiative begins:

1. Review initiative needs
2. Check whether the required reusable element already exists
3. If it exists and is complete, reuse it
4. If it does not exist or must be improved globally, add/update the relevant global task here
5. Keep initiative-specific execution in the initiative `tasks.md`

When a global item is completed:
- mark it `done`
- keep the output path clear
- future initiatives should skip recreating it and simply reference it

---

## Review Notes
This file should evolve as the reusable system grows.

Examples of future global tasks:
- introduce a second canvas family
- improve product shell anatomy
- standardize a new summary-state component
- refine Teams host behavior
- improve table pattern
- add a new global visualization standard
