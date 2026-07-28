<p align="center"><img src="https://raw.githubusercontent.com/go-datetime/brand/main/social/go-datetime.png" width="720" alt="go-datetime"></p>

# go-datetime

Lenient real-world date/time parsing for Go — the messy wire-date format zoo (RFC 822/1123/2822/3339/5322, asctime, HTTP, 2-digit years, ISO 8601, named-zone abbreviations) in one shared library, so every consumer stops reinventing its own layout table.

Pure-Go, `CGO_ENABLED=0`, BSD-3-Clause, 100%-tested, 9-arch CI.

## Repositories

- **[dates](https://github.com/go-datetime/dates)** — the lenient parser (`Parse`, `ParseIn`, `ParseZoneAbbrev`). Used by go-newsgroups/nntp, go-syndication/feed and go-ruby's `Time.parse` (via go-composites/time).
