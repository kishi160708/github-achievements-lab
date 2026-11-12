# git archive

Ekspor tree commit ke arsip tanpa .git.

```text
`git archive --format=tar.gz -o out.tgz HEAD` — snapshot HEAD
`git archive HEAD <path>` — hanya subdirektori
```

> Alternatif unduhan rilis; sisi server GitHub punya endpoint tarball (`gh api repos/o/r/tarball`).
