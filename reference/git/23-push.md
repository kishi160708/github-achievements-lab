# git push

Mengunggah commit lokal ke remote.

```text
`git push origin <branch>` — push branch
`git push -u origin <branch>` — push pertama + set upstream
`git push origin <local>:<remote>` — beda nama branch
`git push --tags` — unggah tag
```

> Bukti push bukan echo '[new branch]': `git ls-remote origin <branch>` harus sama dengan `git rev-parse HEAD`.
