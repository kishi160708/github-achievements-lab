# git init

Membuat repository Git baru di direktori saat ini.

```text
`git init` — inisialisasi repo dengan branch default dari config (init.defaultBranch)
`git init -b main` — inisialisasi dengan branch awal `main`
`git init --bare <dir>` — repo bare untuk server (tanpa working tree)
```

> Set `init.defaultBranch main` di config global agar konsisten.
