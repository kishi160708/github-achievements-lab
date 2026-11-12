# git rebase

Memindahkan rangkaian commit ke base baru.

```text
`git rebase <base>` — replay commit di atas base
`git rebase -i HEAD~n` — interactive: reorder/squash/edit
`git rebase --abort` — kembali seperti semula
`git pull --rebase` — fetch + rebase alih-alih merge
```

> Jangan rebase branch yang sedang dikerjakan orang lain atau yang sudah di-push — menuntut force push.
