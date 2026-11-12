# git diff

Menampilkan perbedaan antara commit, working tree, dan index.

```text
`git diff` — unstaged changes
`git diff --staged` — staged changes (siap commit)
`git diff <a>..<b>` — antara dua commit/branch
`git diff --stat` — ringkasan file + jumlah baris
`git diff -w` — abaikan perubahan whitespace
```

> Gunakan `-w` untuk mengklasifikasikan pass `cargo fmt`/`prettier`: numstat kosong = pure formatting.
