# homebrew-kith

Homebrew tap for [kith](https://github.com/Ying-Kai-Liao/kith).

```
brew install Ying-Kai-Liao/kith/kith
```

`Formula/kith.rb` is written by kith's release workflow: on each `v*` tag it fills the formula with that release's
version and checksums, attaches it to the GitHub Release and commits it here (`scripts/update-tap.sh`, with the
`HOMEBREW_TAP_TOKEN` secret in the kith repo). Without that secret the workflow warns and leaves this repo as it was;
copy the release's `kith.rb` to `Formula/kith.rb` by hand then.
