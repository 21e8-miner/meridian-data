# Meridian data

Price history for [Meridian](https://github.com/21e8-miner/meridian)'s shared page,
https://21e8-miner.github.io/meridian/. This site holds the broad tier: US stocks and ETFs beyond the
S&P 500 and the main funds, and the members of world stock indexes, with five years of daily bars.
The app reads it as a second data site ("shard"), so the data set is not limited by one GitHub
Pages site's size.

Nothing here is meant to be opened directly. Everything is built by `.github/workflows/pages.yml`,
which runs Meridian's own `tools/snapshot.py --part=broad`; the workflow's source of truth is
`data-site/pages.yml` in the meridian repository.
