# git grep

Mencari string di file tertrack — cepat, tanpa menyentuh file tidak tertrack.

```text
`git grep 'pattern'` — cari di working tree tertrack
`git grep 'pattern' <sha> -- '*.py'` — cari di commit tertentu, filter glob
```

> Mencari di commit tertentu jauh lebih cepat daripada checkout hanya untuk grep.
