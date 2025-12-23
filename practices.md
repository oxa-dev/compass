---
title: Practices & Processes
---

These are guidelines not rules; use your best judgment.
If you are unsure or want to talk something through, ask questions in [Discord](https://discord.oxa.dev).

## Development Practices

### Issue Tracking

- Use GitHub Issues for bug reports, feature requests; see [repository list](#repositories)
- Ask public questions in [GitHub Discussions](https://github.com/orgs/oxa-dev/discussions)

### Branching Strategy

- `main` branch: Stable, release-ready code
- Use **squash merges** to keep the main branch simple

### Code Reviews

- Changes should have pull request review
- At least one Steering Council member approval for significant changes
- Automated testing should pass before merge
- Merge optimistically, especially if you are building on the change
- If you need a review/merge and aren't getting attention, send a message in [Discord](https://discord.oxa.dev)

## Decision-Making Process

### Proposals

- Major changes require a proposal document, see the [RFC process](./rfc.md) for more information
- Proposals include motivation, detailed design, alternatives considered, migration path

### Consensus Building

- Aim for consensus among active contributors
- If consensus cannot be reached, Steering Council makes final decision
- Decisions are documented and communicated clearly
