<div align="center">

# Localization Studio

**A focused, local-first localization workspace for Windows and Linux.**

Manage application translations with clarity, confidence, and control.

**Status: In development** · **Windows and Linux support planned** · **Public installers not yet available**

[Releases](https://github.com/DrRoglaa/localization-studio-releases/releases) · [Report an issue](https://github.com/DrRoglaa/localization-studio-releases/issues) · [Developer website](https://itsroglic.com)

</div>

---

## About Localization Studio

Localization Studio is an independently developed desktop application for working with software localization files. Its initial focus is Apple's **`.xcstrings` string catalogs**, with a native desktop experience designed for both Windows and Linux.

The goal is a straightforward, reliable workflow: browse translation keys, review language coverage, edit supported translations, and save catalog changes without silently damaging unrelated data.

> **Current availability:** This repository does not contain downloadable installers yet. Localization Studio `v0.1.0` is at its foundation stage; the current interface uses demonstration data and is **not yet a functional `.xcstrings` editor**.

## What we're building

- **Organized language workspace** — Navigate languages, string keys, source text, developer comments, and translation states.
- **Search and review** — Find strings quickly, filter translation work, and monitor completion across languages.
- **Safe `.xcstrings` editing** — Preserve existing catalog metadata and unsupported structures, validate edits, and guard against accidental overwrites.
- **Local-first workflow** — Work with files stored on your own computer, without needing an account or cloud service for core editing.
- **Comfortable desktop experience** — Light and dark themes, accessible controls, and keyboard-friendly workflows.
- **Future extensibility** — Advanced plural/device variations, validation tools, and optional AI-assisted translation are planned for later milestones.

These describe the product direction, **not a claim that all features are available today**.

## Downloads

Official Windows and Linux packages will appear in this repository's **[GitHub Releases](https://github.com/DrRoglaa/localization-studio-releases/releases)** section once they have passed validation.

| Platform | Planned formats | Current availability |
| --- | --- | --- |
| Windows (x64) | `.exe` installer, `.msi` | Not released |
| Linux (x86-64) | `.AppImage`, `.deb`, `.rpm` | Not released |

System requirements, supported distributions, installation steps, checksums, and any signing information will be documented with each published release. Please do not download installers claimed to be official from unrelated websites.

## Development roadmap

| Milestone | Scope | Status |
| --- | --- | --- |
| **M0 — Foundation** | Desktop shell, demonstration workspace, themes, basic CI and testing | Linux development build verified; not a public release |
| **M1 — Catalog engine** | Read and validate `.xcstrings`, including preservation of unsupported data | Planned |
| **M2 — Workspace** | Real catalog navigation, search, languages and translation progress | Planned |
| **M3 — Editing and save** | Supported translation editing, undo/redo, safe writes and conflict handling | Planned |
| **Later milestones** | Advanced variations, quality checks, optional AI support and distribution polish | Planned |

Roadmap details and timing may change as the application is tested against real-world files.

## Privacy and security

Localization Studio is being designed around **local ownership of localization files**. Core catalog work is intended to run on-device, without mandatory sign-in or telemetry. Any future online translation feature would be optional and separately disclosed.

When releases become available, download them from the [official release page](https://github.com/DrRoglaa/localization-studio-releases/releases) and verify published checksums where provided. Security-sensitive issues should not include confidential translation files, credentials, or API keys in a public report.

## Feedback and support

Have a feature suggestion or encounter a problem with a published build? Use [GitHub Issues](https://github.com/DrRoglaa/localization-studio-releases/issues) if enabled. When reporting a bug, please include your operating system and version, application version, reproduction steps, and a sanitized example when relevant.

For information about the independent developer, visit [itsroglic.com](https://itsroglic.com).

## Repository and licensing

**This is the public distribution repository.** It is intended for release notes, installation documentation, checksums, and compiled Windows/Linux downloads. The application's development source code is maintained in a **separate private repository**.

Public access to binaries does not imply that the application's proprietary source code is open source. Third-party license notices and applicable distribution terms will be provided with releases.

Localization Studio is independently developed and is not affiliated with or endorsed by Apple Inc.

---

<div align="center">

**Independent software, built with ♥ by indie developer David Rok Roglič in Slovenia.**

[itsroglic.com](https://itsroglic.com)

© 2026 Localization Studio. All rights reserved.

</div>
