# gh auth

Autentikasi GitHub CLI.

```text
`gh auth status` — cek akun aktif + scope token (preflight wajib per sesi)
`gh auth login` — alur login interaktif
`gh auth refresh -s repo` — tambah scope token
`gh auth switch -u <user>` — pindah antar akun
```

> `gh auth status` adalah otoritas identitas — jangan mengandalkan ingatan handle/repo.
