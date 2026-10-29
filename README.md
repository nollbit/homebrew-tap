# nollbit/homebrew-tap

```sh
brew install nollbit/tap/monolepo
```

Installs `monolepo`, `docker-credential-monolepo` and `lore` (the Lore client
bundled in `monolepo`, authorized by `monolepo login`). Supported on macOS
Apple Silicon and Linux (x86_64, ARM64).

`Formula/monolepo.rb` follows the release running on monolepo.com: a scheduled
workflow regenerates it from `https://monolepo.com/tools/manifest.json` every
15 minutes and commits when the version changes. Downloads are
content-addressed, so an outdated formula fails its download instead of
installing a different binary.
