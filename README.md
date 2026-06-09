# Omnistudio Omniscripts

Salesforce Omnistudio Omniscripts — guided UI workflows, elements, actions, best practices. LLM-ready reference docs distilled from official Salesforce Help.

## Purpose

This repository is a curated, LLM-ready knowledge base for use with [Context7](https://context7.com). It contains structured Markdown documents distilled from the official Salesforce Help — Omnistudio section, intended to provide AI coding assistants with up-to-date, accurate context when working on Salesforce FSC/Industries solutions.

## Source

All content is derived from the [official Salesforce Help — Omnistudio](https://help.salesforce.com/s/articleView?id=xcloud.os_omniscripts_8355.htm&type=5) documentation. Each `.md` file includes a `Source:` link to its original article.

## Contents

- [`00-overview.md`](./00-overview.md) — Omniscripts
- [`01-working-with-omniscripts.md`](./01-working-with-omniscripts.md) — Working with Omniscripts
- [`02-build-with-elements.md`](./02-build-with-elements.md) — Build an Omniscript with Elements
- [`03-take-actions.md`](./03-take-actions.md) — Take Actions with Omniscripts
- [`04-best-practices.md`](./04-best-practices.md) — Omniscript Best Practices
- [`05-element-reference.md`](./05-element-reference.md) — Omniscript Element Reference
- [`06-group-elements.md`](./06-group-elements.md) — Omniscript Group Elements
- [`07-input-elements.md`](./07-input-elements.md) — Omniscript Input Elements
- [`08-action-elements.md`](./08-action-elements.md) — Omniscript Action Elements
- [`catalog.md`](./catalog.md) — Drill-down index (147 additional pages)

## Best Practices (LLM Rules)

When AI assistants use this library, they should follow these guidelines:

- Use Omniscripts for guided user-facing workflows (forms, wizards), not for backend-only orchestration.
- For backend orchestration use Integration Procedures instead.
- Always preview and test Omniscripts before activation.
- Use Data Mapper actions to read/write Salesforce data, not direct DML.
- For complex UI customization, prefer custom LWC over heavy CSS overrides.

## Usage with Context7

```
use context7
```

Add `use context7` to your prompt in supported clients (Cursor, Claude Code, OpenCode, etc.) to ground responses in this documentation.

## License

Documentation content © Salesforce, Inc. — used for reference under fair use for AI-assisted development. Repository structure and curation: MIT.

## Related Repositories

- [context7-llm-omnistudio-omniscripts](https://github.com/slorenzot/context7-llm-omnistudio-omniscripts)
- [context7-llm-omnistudio-integration-procedures](https://github.com/slorenzot/context7-llm-omnistudio-integration-procedures)
- [context7-llm-omnistudio-data-mappers](https://github.com/slorenzot/context7-llm-omnistudio-data-mappers)
- [context7-llm-omnistudio-security](https://github.com/slorenzot/context7-llm-omnistudio-security)
- [context7-llm-omnistudio-limits](https://github.com/slorenzot/context7-llm-omnistudio-limits)
- [context7-llm-omnistudio-patterns](https://github.com/slorenzot/context7-llm-omnistudio-patterns)
