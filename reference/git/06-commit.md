# git commit

Merekam isi staging area menjadi commit baru.

```text
`git commit -m "pesan"` — commit dengan pesan
`git commit -m "judul" -m "body"` — multi-paragraf
`git commit --amend` — perbaiki commit terakhir (jangan di-commit yang sudah di-push)
`git commit -- <path>` — lock commit pada pathspec eksplisit
Trailer `Co-authored-by: Nama <email>` di pesan = co-authored commit
```

> Lock commit dengan pathspec di shared index: mencegah file stage milik sesi lain ikut.
