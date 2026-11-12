# gh issue

Mengelola issue.

```text
`gh issue create -t judul -b body` — buat
`gh issue close <n> -c "komentar"` — tutup
`gh issue list --state open` — daftar
`gh issue view <n> --comments` — baca diskusi
```

> `gh issue list` HANYA issue; endpoint REST /issues mencampur PR — filter `pull_request == null`.
