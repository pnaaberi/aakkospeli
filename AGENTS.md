# Aakkospeli maintenance

- Read this file and README.md; verify source custody and a clean Git baseline before changes.
- Preserve the single-file, zero-build Finnish alphabet game, keyboard access and local-only scores. Do not add accounts, analytics, uploads or a backend during maintenance.
- Keep real player names/scores, credentials, QA evidence and repository control files out of public application assets. Legacy Pages must exclude AGENTS.md and other control metadata.
- Reuse existing named style tokens for UI work; do not refactor visuals for security-workflow changes. UI changes need real browser/accessibility checks.
- Preserve required static checks and least-privilege, pinned CodeQL analysis. Never bypass checks, disable queries or dismiss real findings to obtain green.
- Check preserved HTML/assets and Pages exclusions after hosting-config changes. A successful scanner is not universal security, browser or device certification.
- Update affected README/release notes, commit only scoped source and distinguish GitHub publication from native/runtime adoption.
