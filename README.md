# scoop-bucket

[![Tests](https://github.com/IdanReed/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/IdanReed/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/IdanReed/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/IdanReed/scoop-bucket/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) bucket for my build of [Herdr](https://github.com/IdanReed/herdr),
a fork of [herdrdev/herdr](https://github.com/herdrdev/herdr) with pane, tab,
spaces, and agents modes and optional space headings in the agents panel.

## Install

```pwsh
scoop bucket add idan https://github.com/IdanReed/scoop-bucket
scoop install idan/herdr
```

Update with `scoop update herdr`. The Windows builds come from the
[fork's releases](https://github.com/IdanReed/herdr/releases), and the
Excavator workflow updates `bucket/herdr.json` when a new one is published.
