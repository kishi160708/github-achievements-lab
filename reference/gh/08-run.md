# gh run

Menonton dan mendiagnosa workflow run (Actions).

```text
`gh run list --limit 5` — run terakhir
`gh run view <id> --log-failed` — log step yang gagal
`gh run watch <id>` — live
`gh run rerun <id>` — ulangi
```

> CI merah yang hilang saat di-rerun = flake; rerun 1x sebelum diagnosis kode.
