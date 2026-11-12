# git tag

Menandai titik tertentu di history (biasanya rilis).

```text
`git tag` — daftar tag
`git tag v1.0` — tag ringan
`git tag -a v1.0 -m "Rilis 1.0"` — annotated (dianjurkan)
`git push origin v1.0` — tag tidak ikut push biasa!
```

> Lupakan `push origin --tags` bisa membuat CI/release yang dipicu tag tidak jalan.
