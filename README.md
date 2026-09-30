# Scoop bucket for lsmd, lsnet and lshn

[![Tests](https://github.com/sanford/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/sanford/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/sanford/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/sanford/scoop-bucket/actions/workflows/excavator.yml)

[lsmd](https://github.com/sanford/lsmd), a terminal-friendly Markdown reader built for navigating large projects, [lsnet](https://github.com/sanford/lsnet), which shows what's on your local network, and [lshn](https://github.com/sanford/lshn), a terminal Hacker News reader, for [Scoop](https://scoop.sh) on Windows.

```pwsh
scoop bucket add sanford https://github.com/sanford/scoop-bucket
scoop install sanford/lsmd
scoop install sanford/lsnet
scoop install sanford/lshn
```

`scoop update lsmd` (or `lsnet`, or `lshn`) brings it up to date. The manifests follow the releases by themselves: every few hours, the Excavator workflow looks for new releases and updates the versions and checksums.

Problems with the programs themselves go to their issues: [lsmd](https://github.com/sanford/lsmd/issues), [lsnet](https://github.com/sanford/lsnet/issues), [lshn](https://github.com/sanford/lshn/issues).
