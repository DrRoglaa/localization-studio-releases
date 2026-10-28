<div align="center">

# Localization Studio

**A focused, local-first localization workspace for Windows and Linux.**

*Software localization should be clear, reliable, and enjoyable.*

**Independent desktop application · In development · No public installers yet**

[**Releases**](https://github.com/DrRoglaa/localization-studio-releases/releases) · [**Report an issue**](https://github.com/DrRoglaa/localization-studio-releases/issues/new/choose) · [**Website**](https://itsroglic.com)

</div>

---

## About

I'm **David Rok Roglič**, an independent software developer in Slovenia, and I'm building **Localization Studio** for developers who manage software translations on Windows and Linux.

My initial focus is Apple's **`.xcstrings` string catalogs**. I want to make it easy to explore string keys and languages, understand translation progress, edit supported values, and preserve a catalog's existing structure safely.

> [!IMPORTANT]
> **Localization Studio isn't available for public download yet.** The `v0.1.0` foundation has been tested locally on Linux, but the current UI uses demonstration data. Real `.xcstrings` reading and editing are planned for subsequent milestones; Windows packaging has not yet been verified.

## The experience I'm building

| Area | My goal |
| --- | --- |
| **Clear workspace** | Browse languages, translation keys, source strings, comments, and status in one place. |
| **Reliable editing** | Preserve unknown catalog metadata and unsupported variations rather than silently rewriting or removing them. |
| **Fast review** | Search, filter, and check translation progress without unnecessary complexity. |
| **Local-first** | Keep core catalog work on your computer without requiring an account or cloud service. |
| **Cross-platform** | Deliver a consistent, keyboard-friendly desktop experience on Windows and Linux. |
| **Future tools** | Add more validation options, advanced variations, and optional AI-assisted translation when the core is dependable. |

These are product goals, not claims that all features are already implemented.

## Downloads

Once public builds have passed the relevant checks, I'll publish them under [**GitHub Releases**](https://github.com/DrRoglaa/localization-studio-releases/releases).

| Operating system | Intended distribution formats | Availability |
| --- | --- | --- |
| Windows (x64) | `.exe` installer, `.msi` | Not released |
| Linux (x86-64) | `.AppImage`, `.deb`, `.rpm` | Not released |

Minimum system requirements and installation instructions will be published alongside tested installers. I won't present an unverified build as a stable release.

## Development roadmap

| Milestone | Focus | Status |
| --- | --- | --- |
| **M0 · Foundation** | Tauri/Rust/React desktop shell, sample UI, themes, testing, development tooling | Linux foundation verified; no public release |
| **M1 · Catalog engine** | Parse and validate `.xcstrings`, preserve unsupported data safely | Planned |
| **M2 · Workspace** | Navigate real keys, languages, progress, and search results | Planned |
| **M3 · Editing and saving** | Supported translation edits, undo/redo, safe saves, conflict handling | Planned |
| **Later** | Advanced variants, quality checks, optional AI features, verified installers | Planned |

The roadmap may change as I test real-world catalogs and platform behavior. See [the full roadmap](ROADMAP.md).

## Help shape Localization Studio

As a solo developer, I value clear, focused feedback. I use structured GitHub issue forms to keep reports actionable:

- [**Report a bug**](https://github.com/DrRoglaa/localization-studio-releases/issues/new?template=01-bug-report.yml) — Describe unexpected behavior in a build you tested.
- [**Suggest a feature**](https://github.com/DrRoglaa/localization-studio-releases/issues/new?template=02-feature-request.yml) — Explain the problem you'd like the app to solve.
- [**Get installation help**](https://github.com/DrRoglaa/localization-studio-releases/issues/new?template=03-installation-help.yml) — Ask about supported packages and setup.

Please remove private strings, API keys, usernames, local paths, and confidential project data from screenshots and logs before sharing them. **For security vulnerabilities, read [Security](SECURITY.md) instead of opening a public issue.**

## Project information

| Page | Details |
| --- | --- |
| [**Roadmap**](ROADMAP.md) | Planned milestones and readiness criteria |
| [**Support**](SUPPORT.md) | Help, troubleshooting, feedback, and issue reporting |
| [**Security**](SECURITY.md) | Responsible vulnerability reporting and supported releases |
| [**Copyright**](COPYRIGHT.md) | Ownership, distribution terms, and third-party notices |
| [**Donations**](DONATE.md) | Ways to support independent development |

## Source and distribution

This **public repository is for distribution and project information**. The application's development source is maintained in a separate **private repository**. Public access to a download does not imply that the application is open source.

Localization Studio is an independent project and is not affiliated with or endorsed by Apple Inc.

---

<div align="center">

**Independent software, built with ♥ by indie developer David Rok Roglič in Slovenia.**

[itsroglic.com](https://itsroglic.com)

© 2026 Localization Studio. All rights reserved.

</div>
