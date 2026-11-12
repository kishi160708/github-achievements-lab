# git clone

Menyalin repository remote beserta seluruh history.

```text
`git clone <url>` — clone standar
`git clone --depth 1 <url>` — shallow clone, hanya 1 commit (hemat bandwidth)
`git clone -b <branch> <url>` — langsung checkout branch tertentu
`git clone --recurse-submodules <url>` — clone beserta submodule
```

> Shallow clone tidak bisa melayani fetch history lengkap sampai di-unshallow (`git fetch --unshallow`).
