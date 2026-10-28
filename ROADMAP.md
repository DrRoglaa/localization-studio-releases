# Development roadmap

[← Back to README](README.md)

I'm building Localization Studio incrementally, validating each foundation before I expand the editing workflow.

| Milestone | Scope | State |
| --- | --- | --- |
| **M0: Foundation** | Tauri 2, React/TypeScript interface, Rust workspace, tests, Linux development launch | Verified locally on Linux; public distribution pending |
| **M1: Catalog engine** | Parse `.xcstrings`, validate input, preserve unknown fields and variations | Planned |
| **M2: Workspace** | Real files, language switching, search, translation status, progress | Planned |
| **M3: Editing** | Simple translation editing, undo/redo, conflict detection, recoverable save | Planned |
| **Later** | Advanced variations, validation rules, optional AI translation, format expansion | Planned |

## Release principles

- **Protect localization data first.** If a change could silently damage a catalog, I won't publish it as a supported editing feature.
- **Test both target platforms.** Passing Linux tests alone doesn't establish Windows compatibility.
- **Keep online features optional.** The core workflow is intended to work locally without an account.
- **Be precise about readiness.** A technical preview isn't a stable release, and an installer won't be listed until its package has been validated.

Dates, features, and platform support may change as I test the implementation. Suggest a useful improvement through the [feature request form](https://github.com/DrRoglaa/localization-studio-releases/issues/new?template=02-feature-request.yml).
