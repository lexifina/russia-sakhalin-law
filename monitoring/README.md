<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Sakhalin Oblast only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 06:02 UTC, Sakhalin Oblast: Official Internet Portal of Legal Information (region65): 10 addresses read; 1 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Sakhalin Oblast: Official Internet Portal of Legal Information (region65)](http://publication.pravo.gov.ru/documents/block/region65) | `zakony-<year>/` | daily | 2026-11-28 06:02 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 06:01](checks/2026-11.md#ru-pravo-sakhalin-20261128t060134z) | pravo-sakhalin | 10 | 1 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-sakhalin-law/compare/99b299de14e3...eba34a9db0bf) |
| [2026-11-27 05:51](checks/2026-11.md#ru-pravo-sakhalin-20261127t055121z) | pravo-sakhalin | 10 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-26 05:56](checks/2026-11.md#ru-pravo-sakhalin-20261126t055635z) | pravo-sakhalin | 10 | 6 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-sakhalin-law/compare/5c2b12f2e92b...ae819ef74273) |
| [2026-11-25 06:31](checks/2026-11.md#ru-pravo-sakhalin-20261125t063138z) | pravo-sakhalin | 10 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 14:43](checks/2026-11.md#ru-pravo-sakhalin-20261124t144312z) | pravo-sakhalin | 11 | 2 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-sakhalin-law/compare/1c0c4806cf14...aa4cc351c53c) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
