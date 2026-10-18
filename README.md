# scoop-binbard

A [Scoop](https://scoop.sh) bucket for Windows applications.

[![CI](https://github.com/binbard/scoop-binbard/actions/workflows/ci.yml/badge.svg)](https://github.com/binbard/scoop-binbard/actions/workflows/ci.yml)
[![Excavator](https://github.com/binbard/scoop-binbard/actions/workflows/excavator.yml/badge.svg)](https://github.com/binbard/scoop-binbard/actions/workflows/excavator.yml)

## Install

```powershell
scoop bucket add binbard https://github.com/binbard/scoop-binbard
scoop install binbard/send
scoop install binbard/markpad
```

Both apps support Windows x64 and ARM64. `send` installs the `send` command;
Markpad installs a Start menu shortcut to its portable executable.

## Updates

Run `scoop update` to refresh buckets, then `scoop update send markpad` to update
installed apps. [Excavator](https://github.com/ScoopInstaller/GithubActions#excavator)
checks upstream releases every four hours and commits new manifest versions and
hashes automatically. It can also be run manually from the repository's Actions
tab. Its schedule runs only while GitHub Actions remains enabled for this repo.

## Sources

- [send-cli](https://github.com/binbard/send-cli)
- [Markpad](https://github.com/sftwrdotdev/Markpad)

This bucket was created from [ScoopInstaller/BucketTemplate](https://github.com/ScoopInstaller/BucketTemplate).
