---
title: Open Exchange Architecture
site:
  hide_outline: true
---

The **Open Exchange Architecture (OXA)** is a specification for representing scientific documents and their components as structured JSON objects. It’s designed to enable **exchange, interoperability, and long-term preservation** of scientific knowledge, while remaining compatible with modern web and data standards.

> **A foundation for interoperable, structured scientific content.**
> OXA defines open, extensible JSON schemas that describe modular and composable scientific documents — bridging the gap between authoring systems like **Stencila**, **MyST**, **Quarto** and the scientific publishing ecosystem which uses tools like **JATS**.

## Overview

OXA provides schemas and examples for representing:

- Executable and interactive research components
- Text, math, figures, code, and metadata
- Authors, affiliations, funding, and licenses
- Parts like abstracts, data-availability, and acknowledgements
- Hierarchical structures like sections and paragraphs
- Inline formatting (strong, emphasis, quote, etc.)

The format is inspired by [JATS](https://jats.nlm.nih.gov), **[unified.js](https://unifiedjs.com)**, and **Pandoc AST**, following a **typed node model** with `children` arrays that form a tree.

## Design Principles

- **Open by design:** JSON Schema–based and CC0-licensed for reuse and extension.
- **Composable:** Each node is self-contained, typed, and can be nested or reused.
- **Interoperable:** Compatible with MyST Markdown, Stencila, Quarto, and similar formats.
- **Extensible:** Add new node types while preserving schema validation.
- **Typed & linked:** Everything has a clear `type`, optional `id`, and structured `data` field.
- **Modular**: Documents and components can link across projects, enabling rich cross-references, citations, and reuse of figures, data, or methods from distributed sources.
- **Computational**: Build in the schemas for computational scientific content (e.g. Notebooks)

## Supporters

OXA stands on the shoulders of open projects that make interoperability in science possible. These organizations are supporting the efforts of OXA financially and with in-kind contributions:

- [Continuous Science Foundation](https://csf.now) — advancing a movement toward continuous, connected, and transparent research communication.
- [openRxiv](https://openrxiv.org) — building open infrastructures for federated preprints and modular scientific publishing.
- [Stencila](https://stenci.la) — open tools for executable documents, bridging computation and publishing.
- [Curvenote](https://curvenote.com) — scientific content management and publishing infrastructure built on MyST and open standards.
- [Posit (Quarto)](https://quarto.org) — an open-source publishing system for scientific and technical communication, supporting reproducible research and interoperability.
- [Creative Commons](https://creativecommons.org) — defining open licenses and rights frameworks that make scientific reuse possible.
- [The Navigation Fund](https://www.navigation.org) - supported the [standards meeting](https://articles.continuousfoundation.org/articles/scientific-standards-meeting) where OXA was created.

## Get Involved 🚀

OXA is an **open community specification**, stewarded by [Continuous Science Foundation](https://continuousfoundation.org/), a grassroots, community-driven organization that brings together researchers, tool builders, publishers, and standards groups to support modular, continuous ways of publishing research.
We welcome contributions from tool builders, publishers, and researchers who want to advance interoperable, open science.

- Extend the schema for your tools
- Discuss interoperability on issues
- Submit examples and validators

> **Join us in building the foundation of a more connected scientific ecosystem.**

- [Slack](https://slack.continuousfoundation.org)
