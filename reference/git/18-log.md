# git log

Menelusuri history commit.

```text
`git log --oneline -5` — 5 commit terakhir, ringkas
`git log --oneline --graph --all` — grafik semua branch
`git log -p <file>` — history + patch per file
`git log --author=kishi` — filter penulis
`git log --format='%h %cr %s' -4` — format kustom + waktu relatif
```

> Waktu relatif (`%cr`) dipakai untuk mengukur liveness sesi lain di shared repo: commit berumur menit = sedang aktif.
