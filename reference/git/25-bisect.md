# git bisect

Pencarian biner commit yang memperkenalkan bug.

```text
`git bisect start` — mulai
`git bisect bad <sha>` — commit yang bermasalah
`git bisect good <sha>` — commit yang masih baik
`git bisect run <cmd>` — otomatis (exit 0 = good)
`git bisect reset` — selesai
```

> Wajib untuk regresi di repo besar: log2(N) langkah, bukan N.
