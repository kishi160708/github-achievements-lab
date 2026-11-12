# git restore

Memulihkan file working tree atau staging (Git 2.23+).

```text
`git restore <file>` — buang perubahan working tree (destruktif!)
`git restore --staged <file>` — unstage tanpa mengubah isi file
`git restore --source=<sha> <file>` — pulihkan dari commit tertentu
```

> Kombinasi klasik: `git reset --soft HEAD~1 && git restore --staged .` untuk membongkar commit dan mempertahankan isi.
