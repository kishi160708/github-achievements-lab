# git merge

Menggabungkan branch lain ke branch saat ini.

```text
`git merge <branch>` — merge biasa (fast-forward bila bisa)
`git merge --no-ff <branch>` — selalu buat merge commit
`git merge --squash <branch>` — gabung perubahan ke index tanpa merge commit
`git merge --abort` — batal saat konflik
```

> Jangan merge saat branch lain sedang commit ke worktree yang sama; baca ulang `git log` tepat sebelum.
