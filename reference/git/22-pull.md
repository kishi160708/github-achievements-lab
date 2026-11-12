# git pull

fetch + merge (atau rebase) branch upstream.

```text
`git pull` — fetch + merge
`git pull --rebase` — fetch + rebase
`git pull --rebase origin main` — eksplisit remote & branch
```

> Pull --rebase gagal 'You have unstaged changes' pada shared tree? Jangan stash milik orang lain — commit path milikmu saja lalu push bila origin belum maju.
