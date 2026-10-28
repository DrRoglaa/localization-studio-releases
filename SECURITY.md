# Security policy

[← Back to README](README.md)

I take the integrity of Localization Studio's releases and the safety of localization files seriously.

## Supported versions

There is **no supported public release** at present. The `v0.1.0` foundation is a development milestone, not a general-availability build. Once I publish releases, this page will identify which versions receive security fixes.

## Report a vulnerability privately

Please **do not open a public GitHub issue** containing exploit instructions, sensitive logs, credentials, or security details.

1. Open the [repository's Security page](https://github.com/DrRoglaa/localization-studio-releases/security).
2. If **Report a vulnerability** is available, use GitHub's private vulnerability reporting form.
3. If private reporting is not enabled, open a **non-sensitive** issue requesting a private security contact method. Do not include exploit details in that issue.

Private vulnerability reporting must be enabled by the repository owner before the GitHub form is available. I will review confidential reports and coordinate next steps as appropriate, but I cannot promise a fixed response or resolution timeline.

## Download integrity

When installers are released, obtain them only from [official GitHub Releases](https://github.com/DrRoglaa/localization-studio-releases/releases). Verify published SHA-256 checksums and signatures when provided, and do not trust unofficial mirrors.

## Security principles

My design goals include local-first handling, minimal filesystem permissions, no required account for core editing, explicit opt-in for any future online translation services, and safe catalog-saving behavior. These are **design and verification targets**, not claims that every feature is implemented in the current foundation build.
