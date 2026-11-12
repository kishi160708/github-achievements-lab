# git worktree

Beberapa working tree dari satu repo — isolasi per sesi/worker.

```text
`git worktree add <path> <branch>` — buat worktree di branch itu
`git worktree list` — semua worktree + HEAD
`git worktree remove <path>` — hapus
`git worktree prune` — bersihkan metadata bekas
```

> Satu branch hanya boleh dicheckout di satu worktree. Worktree baru tidak membawa `node_modules` — junction/symlink dulu, jangan install ulang.
