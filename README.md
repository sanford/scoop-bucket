# Scoop bucket for lsmd

[![Tests](https://github.com/sanford/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/sanford/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/sanford/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/sanford/scoop-bucket/actions/workflows/excavator.yml)

[lsmd](https://github.com/sanford/lsmd), a terminal-friendly Markdown reader built for navigating large projects, for [Scoop](https://scoop.sh) on Windows.

```pwsh
scoop bucket add sanford https://github.com/sanford/scoop-bucket
scoop install sanford/lsmd
```

`scoop update lsmd` brings it up to date. The manifest follows lsmd's releases by itself: every few hours, the Excavator workflow looks for a new release and updates the version and checksum.

Problems with lsmd itself go to [its issues](https://github.com/sanford/lsmd/issues).
