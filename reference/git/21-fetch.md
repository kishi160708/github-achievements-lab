# git fetch

Mengunduh commit/branch dari remote tanpa mengubah working tree.

```text
`git fetch origin` — ambil semua update
`git fetch origin <branch>` — satu branch
`git fetch --prune` — bersihkan ref remote yang sudah dihapus
```

> Tracking ref hanya valid setelah fetch sukses; tanpa fetch, `origin/<b>` bisa membaca state basi.
