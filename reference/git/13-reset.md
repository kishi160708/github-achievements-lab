# git reset

Memindahkan HEAD dan (opsional) index/working tree.

```text
`git reset --soft <sha>` — pindahkan HEAD saja; perubahan tetap staged
`git reset <sha>` — default mixed: HEAD + index, working tree utuh
`git reset --hard <sha>` — HEAD + index + working tree (DESTRUKTIF)
`git reset HEAD <file>` — unstage satu file
```

> Soft reset adalah jalur aman membongkar commit yang belum di-push tanpa kehilangan pekerjaan.
