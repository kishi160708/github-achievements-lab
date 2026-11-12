# git notes

Melampirkan catatan tambahan ke commit tanpa mengubah commit.

```text
`git notes add -m "catatan" <sha>` — tambah
`git notes show <sha>` — baca
`git push origin refs/notes/*` — bagikan notes
```

> Notes tidak di-pull/push default — sinkronisasi refs/notes eksplisit.
