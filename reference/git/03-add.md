# git add

Memindahkan perubahan dari working tree ke staging area (index).

```text
`git add <file>` — stage satu file
`git add -p` — stage interaktif per hunk (sangat presisi)
`git add -u` — stage semua file yang SUDAH tertrack (modified/deleted)
`git add <dir>/` — stage direktori
```

> Hindari `git add -A` pada tree bersama; stage path eksplisit agar kerja orang lain tidak ikut ter-commit.
