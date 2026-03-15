# Persona Models

## Purpose
Defines how persona files are used as shared source of truth across initiatives.

## Source of truth
- Individual persona files live under `/docs/personas/`.
- This file references those persona files and defines the common structure.
- If a persona changes, update the individual persona file and treat it as the latest source.

## Personas in scope
- Project Manager
- Program Manager
- Portfolio Manager

## How personas influence behavior
Personas influence:
- bucket meaning
- KPI emphasis
- AI insight emphasis
- default summary/detail balance
- visible actions and permissions
- drill-down depth

## Persona file structure
Each persona file should use this structure:
- Role summary
- Responsibilities
- Objectives
- Pain points
- Emotional context
- Decisions they make
- Data they need to see
- Default action focus
- KPI emphasis
- AI support needs
- Permissions or action scope
- How this persona changes overview-family behavior

## References
- `/docs/personas/pm.md`
- `/docs/personas/program-manager.md`
- `/docs/personas/portfolio-manager.md`
