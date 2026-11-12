# git revert

Membatalkan commit dengan commit baru berlawanan — aman untuk history publik.

```text
`git revert <sha>` — balikkan satu commit
`git revert <sha1> <sha2>` — beberapa sekaligus
`git revert -m 1 <merge-sha>` — revert merge commit (pilih parent 1)
```

> Revert (bukan reset) adalah satu-satunya cara aman membatalkan commit yang sudah di-push.
