# git bundle

Membungkus branch menjadi satu file — transport tanpa jaringan.

```text
`git bundle create repo.bundle --all` — semua ref
`git clone repo.bundle` — gunakan bundle
```

> Berguna saat git transport diblokir total: bawa file, buka di mesin lain.
