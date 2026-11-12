# git config

Membaca/menulis konfigurasi Git pada tiga scope.

```text
`git config --get <key>` — baca (scope efektif)
`git config --get http.proxy` — proxy yang sedang dipakai
`git config --local user.email` — identitas repo ini
`git config --global init.defaultBranch main`
```

> Config adalah otoritas runtime: sebelum menyalin flag dari instruksi (proxy, dsb.), baca config dulu.
