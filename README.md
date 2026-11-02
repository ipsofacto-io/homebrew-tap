# homebrew-tap

[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/ipsofacto-io/homebrew-tap/badge)](https://scorecard.dev/viewer/?uri=github.com/ipsofacto-io/homebrew-tap)

Homebrew casks for [ipso](https://github.com/ipsofacto-io/ipso).

```sh
brew install ipsofacto-io/tap/ipso
```

GoReleaser in `ipsofacto-io/ipso` publishes `Casks/ipso.rb` on each release when `HOMEBREW_TAP_TOKEN` is set on that repository. That secret is not set yet, so this tap is empty. The binary is not notarized, so the cask clears the macOS quarantine flag on install, which a formula install never set.
