# git status

Menampilkan status working tree dan staging area.

```text
`git status` — ringkasan lengkap
`git status -s` — short format (porcelain v1)
`git status -sb` — short + info branch upstream
`git status --porcelain=v1 -uall` — format stabil untuk skrip, termasuk file untracked
```

> Porcelain format adalah satu-satunya output yang dijamin stabil antar versi Git untuk diparsing.
