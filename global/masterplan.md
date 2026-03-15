# Global Masterplan

## Purpose
This file defines the reusable product-system strategy across initiatives.

It is not the masterplan for one single screen or initiative.
Instead, it is the shared source of truth for how the product should be structured, scaled, and evolved across:
- global shell rules
- product shell extensions
- reusable canvas family categories
- persona-driven behavior
- AI behavior
- visualization rules
- view patterns
- host variants
- reusable components and patterns

Initiative-specific work must live under:
- `/docs/initiatives/<initiative-name>/masterplan.md`
- `/docs/initiatives/<initiative-name>/tasks.md`

This global masterplan exists to ensure that new initiatives are assembled from reusable system parts rather than designed from scratch each time.

---

## Core Product Strategy

The product should be built as a reusable system with consistent:
- shell behavior
- canvas family behavior
- persona-driven adaptation
- AI interaction rules
- reusable views and components
- initiative-specific tailoring

The system should support:
- consistency across the product
- flexibility across organizational maturity
- scalability for new domains and future initiatives
- ability to introduce new reusable families, views, and components over time

---

## Source of Truth Model

### Global source of truth
The `/docs/global` folder defines reusable product rules.

### Persona source of truth
The `/docs/personas` folder defines reusable role-based source files.

### Reusable family/pattern source of truth
The following folders define reusable patterns:
- `/docs/families`
- `/docs/views`
- `/docs/components`
- `/docs/shells`

### Initiative source of truth
Each initiative must maintain its own:
- `masterplan.md`
- `tasks.md`
- `app-flow.md`
- `implementation.md`

under:
- `/docs/initiatives/<initiative-name>/`

---

## Product Architecture Model

### 1. Shell
The shell is the global layout frame of a page/screen.

Examples:
- top banner
- side menu
- product header
- host-specific shell variants
- future alternate shell structures such as Teams or Power BI-like screens

Shell behavior must be reusable and centrally controlled.

### 2. Canvas
The canvas is the main purposeful area of the page.

The canvas should not be designed from scratch each time.
It should be selected from reusable family categories where possible.

### 3. Family Category
A family category is a reusable canvas pattern with shared layout and behavior.

Example:
- Operational Overview family

A family category may have variants by:
- placement level
- persona emphasis
- device/responsive mode
- host context

### 4. Persona Alignment
Persona files define:
- responsibilities
- objectives
- pain points
- emotional context
- action focus
- decision needs

Personas influence:
- what is shown first
- what buckets mean
- which KPIs are emphasized
- what AI surfaces
- what actions are available

Personas should influence emphasis and behavior, not force a totally different product language for every role.

### 5. Initiative Tailoring
An initiative tailors the reusable system for a specific domain and purpose.

Examples:
- PM Landing
- Finance Operation

An initiative should:
- reuse global elements first
- tailor only where needed
- create new reusable global elements only if necessary

---

## Reusable Global Layers

The reusable global layers currently include:

- `00_design-system.md`
- `01_shell-rules.md`
- `02_product-shell-extension.md`
- `03_operational-overview-family.md`
- `04_persona-models.md`
- `05_ai-behavior.md`
- `06_visualization-rules.md`
- `07_view-patterns.md`
- `08_host-shell-variants.md`

These files should be treated as reusable building blocks.

---

## Global Design Principles

### Reuse before invention
Always prefer existing reusable global patterns before creating new ones.

### One product, many initiatives
Different initiatives should feel like one coherent product:
- same shell language
- same family behavior where relevant
- same AI behavior rules
- same visual and interaction standards

### Flexible but controlled
The system must support different:
- personas
- domains
- organizational maturity levels
- host environments

while keeping consistent reusable rules.

### Centralized improvement
If a reusable element is improved globally, all initiatives that reference it should benefit from the improvement.

Examples:
- table pattern
- AI panel
- shell behavior
- visualization rules

### Explicit separation of concerns
- global files define reusable rules
- persona files define role truth
- initiative files define initiative-specific decisions
- tasks files define execution order and reuse/new decisions

---

## Theme and Design System Strategy

The design system should support a centrally controlled theme so changes can scale across the product.

This includes:
- design tokens
- typography
- spacing
- color roles
- theme behavior
- reusable component alignment

Fluent UI 9 is the base design-system foundation.

Bryntum v7 components may be selectively used where advanced planning/work-management patterns are needed, but they must align to the same:
- theme
- typography
- spacing
- interaction tone
- product language

Bryntum provides capability, not a separate visual language.

---

## Family Strategy

### Current family
The current reusable family is:

- Operational Overview family

This family supports:
- persona-based overview/operation-center experiences
- visible AI panel + Ask Altus where relevant
- overview summary + action buckets + alternate views
- landing-level and product/sub-level variants
- domain-specific content inside a shared family structure

### Future family growth
Over time, additional family categories may be introduced for:
- deeper action work
- more data-heavy operational areas
- more risk-sensitive workflows
- specialist domain areas requiring different canvas behavior

New families should only be introduced when the current family no longer fits comfortably.

---

## View and Component Strategy

Reusable view patterns and reusable components should be centrally controlled.

Examples:
- board/bucket view
- list view
- table view
- executive summary state
- AI panel
- Ask Altus
- card pattern
- bucket pattern

If a reusable pattern is updated and adopted globally, initiatives using that pattern should inherit the latest approved version.

---

## Host Strategy

The product may appear in different host contexts, such as:
- standard app/web
- Teams
- future embedded contexts

Host differences should primarily affect:
- shell placement
- AI placement
- available space
- responsive behavior

Host changes should not force a redesign of the family category unless the page purpose changes fundamentally.

---

## Initiative Assembly Model

Each initiative should be assembled through deliberate selection of reusable system parts.

Examples of selection:
- shell
- product shell mode
- family category
- persona source files
- AI pattern
- view patterns
- reusable components

If something required for an initiative does not yet exist:
1. identify the gap
2. create it in the correct reusable global location
3. record it in global tasks
4. link the initiative to it for future reuse

---

## Masterplan Relationship to Tasks

This global masterplan defines the reusable system strategy.

Execution and cross-initiative reusable work should be tracked in:
- `/docs/global/tasks.md`

Initiative-specific execution should be tracked only in:
- `/docs/initiatives/<initiative-name>/tasks.md`

---

## Success Criteria

The global system is successful when:
- initiatives can be created by reusing global system parts
- product consistency is maintained across screens and domains
- persona differences shape behavior without breaking the product language
- new reusable elements can be added cleanly
- global improvements scale across initiatives
- the product supports future growth without redesigning the system from scratch
