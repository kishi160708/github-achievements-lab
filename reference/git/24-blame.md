# git blame

Mengetahui siapa yang mengubah tiap baris dan kapan.

```text
`git blame <file>` — per baris
`git blame -L 10,20 <file>` — rentang baris
`git blame -w` — abaikan perubahan whitespace
```

> Blame mengikuti commit terakhir yang menyentuh baris — refactor massal bisa 'menutupi' penulis asli; gunakan `--follow`/history file.
