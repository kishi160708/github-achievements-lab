# Pull Shark — deep dive

Tier 2/16/128/1024 merged PR. Menghitung PR merged di repo mana pun, termasuk repo sendiri (self-merge).

```text
Counter resmi: query `author:<user> is:pr is:merged` via `gh search prs`
Retrospektif: PR lama ikut terhitung
Repo privat ikut dihitung untuk badge (badge tetap tampil publik)
```

> Delay badge hingga 24 jam setelah merge ke-16, ke-128, dst.
