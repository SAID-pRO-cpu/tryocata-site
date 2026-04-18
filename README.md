# tryocata.com — Ocatagroup sending domain bridge page

Minimal variant with a sharper "try it" framing. Canonical points to `getocata.com`. Exists so the domain doesn't 404 when a prospect clicks through from `@tryocata.com` cold email.

## Deploy

```bash
vercel --prod
```

Framework preset: **Other** (static).

## Custom domain

In Vercel project settings → Domains, add `tryocata.com`. Update Namecheap DNS with the A / CNAME records Vercel provides.
