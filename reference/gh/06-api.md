# gh api

Panggilan REST/GraphQL langsung — fallback untuk apa pun yang tidak punya subcommand.

```text
`gh api repos/o/r/contents/<path>` — baca file (content base64)
`gh api -X PUT ... -f field=v` — tulis dengan field form
`gh api graphql -f query='...' -F var=$ID` — GraphQL
`gh api ... --jq '.field'` — saring output dengan jq bawaan
```

> Saat git transport 502, `gh api` sering masih hidup (jalur koneksi berbeda) — gunakan untuk baca state.
