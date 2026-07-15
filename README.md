# RuleCaddie — Marketing Site

Static marketing + legal site for the RuleCaddie iOS app.

- `index.html` — landing page
- `support.html` — support / FAQ (App Store Support URL)
- `privacy.html` — privacy policy (App Store Privacy URL)
- `confirmed.html` — email-confirmation landing page (Supabase auth Site URL)
- `vercel.json` — clean URLs + caching/security headers
- `img/` — app screenshots

## Deploy

Hosted on Vercel (project `rulecaddie`, Fathom Dev team). No git integration
on the Vercel side, so deploys are via CLI:

```bash
vercel deploy --prod --scope fathom-dev
```

Canonical URLs (clean, no `.html`): `/`, `/support`, `/privacy`, `/confirmed`.

## Notes

- App Store button links are placeholders until v1 is approved; swap the real
  App Store URL in all four pages then.
- Custom domain (rulecaddie.com) attaches in the Vercel project settings.
