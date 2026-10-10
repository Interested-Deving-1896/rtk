[update-readmes]   Mode: rewrite — migrating to template structure...
# rtk

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/rtk) [![KDE Eco](https://img.shields.io/badge/KDE%20Eco-certified-brightgreen?logo=kde&logoColor=white&style=flat-square)](https://eco.kde.org/) [![Blue Angel](https://img.shields.io/badge/Blue%20Angel-DE--UZ%20215-0055a4?style=flat-square)](https://www.blauer-engel.de/en/certification/criteria)



<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/rtk.git
cd rtk
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration


`~/.config/rtk/config.toml` (macOS: `~/Library/Application Support/rtk/config.toml`):

```toml
[hooks]
exclude_commands = ["curl", "playwright"]  # skip rewrite for these

[tee]
enabled = true          # save raw output on failure (default: true)
mode = "failures"       # "failures", "always", or "never"
```

When a command fails, RTK saves the full unfiltered output so the LLM can read it without re-executing:

```
FAILED: 2/15 tests
[full output: ~/.local/share/rtk/tee/1707753600_cargo_test.log]
```

For the full config reference (all sections, env vars, per-project filters), see the [Configuration guide](https://www.rtk-ai.app/guide/getting-started/configuration).

### Uninstall

```bash
rtk init -g --uninstall     # Remove hook, RTK.md, settings.json entry
cargo uninstall rtk          # Remove binary
brew uninstall rtk           # If installed via Homebrew
```

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/rtk`](https://github.com/Interested-Deving-1896/rtk) and mirrored through:

```
Interested-Deving-1896/rtk  ──►  OpenOS-Project-OSP/rtk  ──►  OpenOS-Project-Ecosystem-OOC/rtk
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
| Contributor | Commits |
|---|---|
| [@aeppling](https://github.com/aeppling) | 303 |
| [@pszymkowiak](https://github.com/pszymkowiak) | 207 |
| [@FlorianBruniaux](https://github.com/FlorianBruniaux) | 175 |
| [@github-actions[bot]](https://github.com/apps/github-actions) | 65 |
| [@KuSh](https://github.com/KuSh) | 22 |
| [@ousamabenyounes](https://github.com/ousamabenyounes) | 21 |
| [@vsumner](https://github.com/vsumner) | 8 |
| [@claude](https://github.com/claude) | 6 |
| [@Interested-Deving-1896](https://github.com/Interested-Deving-1896) | 6 |
| [@hed0rah](https://github.com/hed0rah) | 6 |
| [@polaminggkub-debug](https://github.com/polaminggkub-debug) | 6 |
| [@heAdz0r](https://github.com/heAdz0r) | 6 |
| [@F0rty-Tw0](https://github.com/F0rty-Tw0) | 5 |
| [@zerone0x](https://github.com/zerone0x) | 5 |
| [@em0t](https://github.com/em0t) | 5 |
| [@tmchow](https://github.com/tmchow) | 5 |
| [@JBF1991](https://github.com/JBF1991) | 5 |
| [@guillaumedeslandes](https://github.com/guillaumedeslandes) | 5 |
| [@kherembourg](https://github.com/kherembourg) | 4 |
| [@mhcoen](https://github.com/mhcoen) | 4 |
| [@scottbrown](https://github.com/scottbrown) | 4 |
| [@TropicalDog17](https://github.com/TropicalDog17) | 4 |
| [@vincenthcui](https://github.com/vincenthcui) | 4 |
| [@swithek](https://github.com/swithek) | 3 |
| [@rtk-release-bot[bot]](https://github.com/apps/rtk-release-bot) | 3 |
| [@niklasmarderx](https://github.com/niklasmarderx) | 3 |
| [@mgierok](https://github.com/mgierok) | 3 |
| [@mvanhorn](https://github.com/mvanhorn) | 3 |
| [@xdm67x](https://github.com/xdm67x) | 2 |
| [@apowis](https://github.com/apowis) | 2 |
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream influences recorded._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## Accessibility

<!-- AI:start:accessibility -->
This repo uses automated accessibility auditing via `check-accessibility.yml`.

Checks include: CODEOWNERS ownership coverage, README screen-reader compatibility,
WCAG 2.1 AA HTML compliance, audio overview (espeak-ng), and Braille output (liblouis).




Run the [Check Accessibility](https://github.com/Interested-Deving-1896/rtk/actions/workflows/check-accessibility.yml)
workflow to generate the first report and accessibility artifacts.
See the [W3C Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/)
for the underlying accessibility reference.
<!-- AI:end:accessibility -->

## License

<!-- AI:start:license -->
[Apache-2.0](https://github.com/Interested-Deving-1896/rtk/blob/master/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
