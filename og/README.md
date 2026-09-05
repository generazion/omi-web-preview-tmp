# OG images

Generate one image per locale (1200x630, < 200 KB):

- `og-es.jpg`
- `og-en.jpg`
- `og-fr.jpg`
- `og-de.jpg`

Suggested workflow until brand assets are final:

```bash
node ../scripts/generate-og.mjs
```

Until that script lands, drop manually exported images here or rely on the
fallback `/og/og-default.jpg`.
