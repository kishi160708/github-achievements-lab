# git submodule

Menanam repo lain sebagai dependensi di dalam repo.

```text
`git submodule add <url> <path>` — tambah
`git submodule update --init --recursive` — inisialisasi setelah clone
`git submodule update --remote` — tarik versi terbaru submodule
```

> Submodule menempel SHA, bukan branch — upgrade eksplisit, tidak otomatis.
