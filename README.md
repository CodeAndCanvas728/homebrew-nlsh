# homebrew-nlsh

The Homebrew formula for [nlsh](https://github.com/CodeAndCanvas728/nlsh) — a
natural-language shell: describe what you want in plain words, a model turns
it into shell commands, and nlsh checks the plan, shows it to you, and runs
it once you approve it.

## Install

```sh
brew tap CodeAndCanvas728/nlsh
brew install codeandcanvas728/nlsh
```

Homebrew 7 asks you to trust a tap before it will use it:

```sh
brew trust codeandcanvas728/nlsh
```

## Where the formula comes from

The formula lives in the nlsh repository, at `homebrew/nlsh.rb`, and is copied
here at each release — the version, the checksums and the tag all move
together. Rebuilding the same source gives the same archives, so the
checksums here are the ones in the release's `SHA256SUMS`.
