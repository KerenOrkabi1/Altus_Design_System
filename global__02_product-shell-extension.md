# Product Shell Extension

## Purpose
Defines how the base shell extends when a product-level header is present.

## Source
- Product header is based on Microsoft Power Apps OOB behavior.
- Product header height: 239px

## Product header anatomy
- Record/context header
- Metadata summary strip
- Lifecycle/stage strip
- Tab list row
- Contextual utility action

## Modes
- Base shell only
- Base shell plus product header
- Landing-style shell without product header

## Rules
- The product shell may appear under the base shell.
- Landing pages may omit the product header and instead use welcome/orientation in the shell.
- Product-level pages may include the product header and still reuse the same canvas family underneath.
- Tabs are part of the product shell, not the canvas family.
- Product shell can be refined later with more exact row behavior and dimensions.
