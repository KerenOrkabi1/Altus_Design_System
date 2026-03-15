# Shell Rules

## Purpose
Defines the global shell for a page. A shell is the global layout frame of the screen.

## Current base shell
- Top banner height: 48px
- Left navigation width: 199px expanded, 43px collapsed
- Top banner background: #616161
- Side navigation background: #f0f0f0
- Canvas background: #f9f9f9

## Shell anatomy
- Top banner
- Left navigation
- Optional welcome/orientation region for landing placement
- Optional product header extension
- Main canvas area
- Optional AI placement depending on family and host rules

## Rules
- Filters belong inside the page, not inside the product header.
- Reusable elements that appear in multiple pages should keep the same layout behavior.
- Shell behavior should be consistent across screen types unless a host or family variant explicitly overrides it.

## Responsive behavior
- Desktop: full shell with AI visible when the active family requires it.
- Medium widths: preserve canvas priority; reduce secondary shell detail before changing family behavior.
- Mobile: shell may switch to a simplified layout while preserving page purpose.
