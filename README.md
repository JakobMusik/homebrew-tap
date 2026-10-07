# homebrew-tap

Homebrew tap for [SelectTTS](https://github.com/JakobMusik/SelectTTS), a macOS menu-bar app that
reads selected text aloud.

```sh
brew install --cask jakobmusik/tap/selecttts
```

Update with `brew upgrade --cask selecttts`.

SelectTTS is signed with the project's own certificate rather than notarized by Apple, so the cask
removes the quarantine flag after installing. The cask here is updated by the release script in the
SelectTTS repository (`scripts/release/build-release.sh`).
