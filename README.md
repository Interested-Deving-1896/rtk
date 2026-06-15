[update-readmes]   Mode: rewrite — migrating to template structure...
# rtk

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/rtk)

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
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[Apache-2.0](https://github.com/Interested-Deving-1896/rtk/blob/master/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
