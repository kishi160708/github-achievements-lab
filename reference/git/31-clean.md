# git clean

Menghapus file untracked (DESTRUKTIF).

```text
`git clean -n` — DRY RUN: hanya tampilkan
`git clean -fd` — hapus file + direktori untracked
`git clean -xd` — termasuk yang diabaikan .gitignore
```

> Selalu -n dulu. Di shared tree, untracked bisa berupa WIP orang lain — jangan bersihkan sembarangan.
