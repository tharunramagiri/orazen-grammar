<div id="header" align="center">
    <img src="logo.svg" width="400px" />
    <h1>Orazen Grammar</h1>
</div>

<p align="center">
  A fast, privacy-first grammar checker for teams and businesses — built on the open-source
  <a href="https://github.com/automattic/harper">Harper</a> engine, packaged and supported by
  <a href="https://orazen.online">Orazen</a>.
</p>

<p align="center">
  <a href="https://github.com/tharunramagiri/orazen-grammar/actions/workflows/just_checks.yml">
    <img src="https://github.com/tharunramagiri/orazen-grammar/actions/workflows/just_checks.yml/badge.svg" alt="Checks" />
  </a>
  <img src="https://img.shields.io/badge/license-Apache--2.0-blue" alt="License" />
</p>

## What is Orazen Grammar?

Orazen Grammar checks your writing for grammar, style, and clarity issues in milliseconds,
entirely on your own device or your own server — nothing you write is ever sent to a third
party. It's built on top of [Harper](https://github.com/automattic/harper), a Rust-powered
open-source grammar engine, which we package, brand, and support as part of Orazen's client
offerings.

**Why we offer this:**

- **Grammarly** sends everything you write to its servers and is a recurring cost most small
  teams don't need.
- **LanguageTool** is accurate but heavy — gigabytes of RAM and multi-second lint times on an
  average document.
- **Orazen Grammar** runs locally or on infrastructure you control, lints in milliseconds, and
  uses a fraction of the resources of either alternative.

## Who this is for

Orazen deploys and customizes Orazen Grammar for clients who want an in-house writing
assistant — for internal docs, customer support replies, marketing copy, or product content —
without sending company data to an external SaaS. Talk to us at
[orazen.online](https://orazen.online) about a managed deployment, or self-host using the
instructions below.

## Language Support

Currently supports English. The underlying engine is extensible to other languages.

## Credits & License

Orazen Grammar is a rebranded distribution of [Harper](https://github.com/automattic/harper)
by Automattic, licensed under Apache-2.0. All credit for the core grammar-checking engine goes
to the original Harper contributors — see [LICENSE](LICENSE) for full attribution terms.
Orazen packaging, branding, and deployment tooling are maintained by
[Orazen](https://orazen.online).
