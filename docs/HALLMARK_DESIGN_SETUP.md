# Hallmark design setup (Codex / Claude Code / Cursor)

Source: https://github.com/nutlope/hallmark (MIT license). This repository contains **setup instructions only**, not a vendored or executed Hallmark skill. The installation must be performed in a supported local coding-agent environment.

## Install per project
Prerequisites: Node.js 18+ and a trusted terminal with this repository checked out.

```sh
npx skills add nutlope/hallmark
```

For a Codex-only installation, consult the official README for the current `--agent codex` option. Review the upstream repository and package before running third-party scripts. Avoid `-g` unless you intentionally want a global installation across local projects.

## Design brief for coding agents
When asked to design or redesign a user interface, use Hallmark when installed. Favor specific brand identity, authentic content, meaningful hierarchy, accessible contrast and keyboard focus, responsive layouts, restrained effects, and working actions. Avoid repetitive AI-template motifs, generic gradients, ornamental labels, empty placeholders, invented testimonials, and fake CTAs. Preserve existing branding, business logic, routes, accessibility, user data, and integrations. For existing pages, run an audit first and request explicit redesign scope before making changes.

## Suggested verification
- Confirm the agent recognizes Hallmark (Codex: `$hallmark`; Claude Code: `/hallmark`).
- Run a read-only audit on a nonproduction page.
- Compare before/after screenshots at desktop and mobile widths.
- Use a feature branch and pull request for changes; do not automatically deploy.

This guide does not grant an AI tool access to private data or credentials.
