# git cherry-pick

Mengambil satu commit tertentu ke branch saat ini.

```text
`git cherry-pick <sha>` — apply satu commit
`git cherry-pick <a>^..<b>` — rentang commit
`git cherry-pick -x <sha>` — tambahkan catatan `(cherry picked from ...)`
```

> Saat shared tree: cherry-pick milikmu ke main alih-alih push seluruh branch yang mengandung commit orang lain.
