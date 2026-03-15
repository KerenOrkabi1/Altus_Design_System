# Design System

## Purpose
This file is the product-wide visual and interaction foundation for Altus. It is the single source of truth for theme, typography, spacing, tokens, and component alignment across the product.

## Core principles
- Fluent UI 9 is the core design-system baseline.
- Bryntum v7 components may be used selectively for advanced work-management patterns.
- Any non-Fluent component must align to the active Altus theme, typography, spacing, and interaction tone.
- Capability may vary by component library, but the visual language must feel like one product.

## Theme
- Theme changes should be controlled centrally from this file.
- A theme update should cascade across all product experiences that inherit these rules.
- Theme includes color roles, typography, spacing, corner radius, elevation, and semantic states.

## Typography
- Typography must stay consistent across shell, canvas, AI panel, views, and reusable components.
- Typography changes should be made once here and inherited everywhere.
- Use a clear enterprise hierarchy: page title, section title, component title, metadata, helper text, state text.

## Spacing and density
- The product is operational and information-dense, but must remain calm and scannable.
- Prefer compact enterprise spacing rather than consumer-style loose layouts.
- Use consistent spacing tokens across shell, canvas, cards, list rows, table cells, and panels.

## Component alignment
- Reusable components should reference the current approved global pattern rather than define their own styling.
- If a component pattern is updated, screens that reference it should inherit the latest approved version.
- Examples include table, list, board, executive summary state block, AI panel, Ask Altus, cards, and bucket patterns.

## Accessibility
- Maintain strong contrast, keyboard support, and readable hierarchy.
- Interactive elements must keep predictable focus states.
- Semantic color must not be the only carrier of meaning.

## Product feel
- Professional, enterprise, operational, calm, and trustworthy.
- Action-focused rather than decorative.
- AI should feel integrated and controlled, not intrusive.
