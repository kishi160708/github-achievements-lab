# git switch

Perintah modern khusus pindah/membuat branch (Git 2.23+).

```text
`git switch <branch>` — pindah branch
`git switch -c <nama>` — buat + pindah
`git switch -` — kembali ke branch sebelumnya
`git switch --detach <sha>` — detached HEAD untuk inspeksi
```

> Detached HEAD menerima commit yang tidak nempel di branch mana pun — commit bisa 'hilang' dari daftar branch.
