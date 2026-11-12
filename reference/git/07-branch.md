# git branch

Membuat, melihat, dan menghapus branch.

```text
`git branch` — daftar branch lokal
`git branch -a` — lokal + remote
`git branch <nama>` — buat tanpa pindah
`git branch -d <nama>` — hapus (aman, harus sudah di-merge)
`git branch -D <nama>` — hapus paksa
`git branch --contains <sha>` — branch mana saja yang memuat commit
```

> Branch lokal yang tidak ada di origin = push queue; cek `git rev-list --count <b> --not --remotes=origin`.
