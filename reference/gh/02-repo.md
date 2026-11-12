# gh repo

Mengelola repository.

```text
`gh repo create o/r --public --add-readme` — buat repo
`gh repo list <user> --json name,visibility` — daftar repo
`gh repo view o/r --web` — buka di browser
`gh repo clone o/r` — clone
`gh repo edit o/r --description "..."` — ubah deskripsi
```

> Token dengan scope `repo` juga mengontrol repo privat; hati-hati saat membuat repo publik di akun kerja.
