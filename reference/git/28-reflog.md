# git reflog

Riwayat pemeriksaan HEAD — penyelamat commit 'hilang'.

```text
`git reflog` — riwayat HEAD
`git reflog <branch>` — riwayat sebuah branch
`git reset --hard HEAD@{2}` — kembali ke posisi 2 langkah lalu
```

> Reflog menyimpan commit yang tidak dicapai branch apa pun (orphan) — cek di sini sebelum menyimpulkan pekerjaan hilang.
