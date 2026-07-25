---
title: tsvsheet.goldmark
---

**tsvsheet.goldmark** is a [goldmark](https://github.com/yuin/goldmark) extension that renders [tsvsheet](https://github.com/tsvsheet/tsvsheet) code blocks as computed tables: a fenced ` ```tsvsheet ` block in markdown is evaluated by the [go-tsvsheet](https://github.com/tsvsheet/go-tsvsheet) engine and rendered in place, so documents show results, not formulas.

It shares its rendering semantics with the other markdown hosts ([tsvsheet.remark](https://github.com/tsvsheet/tsvsheet.remark) for remark/markdown-it) — the same block renders byte-for-byte identically in every host.

- Source: [tsvsheet/tsvsheet.goldmark](https://github.com/tsvsheet/tsvsheet.goldmark)
- Engine: [tsvsheet/go-tsvsheet](https://github.com/tsvsheet/go-tsvsheet)
- Language: [tsvsheet/tsvsheet](https://github.com/tsvsheet/tsvsheet)
