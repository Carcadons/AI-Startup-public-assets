# AI-Startup-public-assets

Public counterpart to [`Carcadons/AI-Startup`](https://github.com/Carcadons/AI-Startup) (private) — the coordination repo for the carcadons agent roster. That repo can't host anything needing a public URL (e.g. images for the Instagram Graph API's publish step), so this repo exists specifically for that purpose.

**Everything in this repo is public and approved for live use.** Nothing unapproved, draft, or sensitive belongs here — drafts and internal work stay in the private repo; only assets that have cleared human review and are about to go live (or are already live) get pushed here.

## Structure

Mirrors the private repo's `platforms/<name>/` convention:

```
platforms/
  stampif/
    social/    approved Instagram post images, referenced by public raw.githubusercontent.com URL at publish time
```

## Working conventions

- No credentials, tokens, or account IDs — same rule as the private repo.
- Images pushed here should be named/dated so they're traceable back to the corresponding entry in the private repo's `platforms/stampif/reports/social/` calendar.
- This repo isn't meant to be browsed as a gallery — it's a URL-hosting mechanism for the publish pipeline. Treat file history/commits as the audit trail.
