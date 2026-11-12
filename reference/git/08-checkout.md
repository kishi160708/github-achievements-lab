# git checkout

Bermove antara branch, commit, atau memulihkan file (versi lama).

```text
`git checkout <branch>` — pindah branch
`git checkout -b <nama>` — buat + pindah
`git checkout <sha> -- <file>` — pulihkan satu file dari commit
`git checkout .` — buang semua perubahan working tree (destruktif!)
```

> Modern: `git switch` untuk pindah branch, `git restore` untuk memulihkan file.
