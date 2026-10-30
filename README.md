# Anvaya Homebrew tap

```sh
brew install NaMan6122/tap/anvaya
```

This installs **both** halves of Anvaya together: the `anv` CLI and the
`mind-daemon` memory daemon. `anv` starts the daemon on demand, so they must
match; the formula always ships the tested pair.

| Platform | Supported |
|---|---|
| macOS, Apple Silicon | yes |
| Linux x86_64 (glibc 2.39+) | yes |
| Linux arm64 (glibc 2.39+) | yes |
| macOS, Intel | not yet |

Upgrade with `brew upgrade anvaya`. Uninstall with `brew uninstall anvaya`.
Your configuration and sessions live in `~/.anvaya` and are never touched.

The formula is generated from the same release channel the curl installer
reads, so Homebrew and `curl ... | sh` always install the same binaries.
Releases, issues and the other install methods are at
<https://github.com/NaMan6122/Anvaya>.
