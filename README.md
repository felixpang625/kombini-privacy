# kombini-privacy

The **public privacy policy** for **Kombini**.

**Live at:** https://felixpang625.github.io/kombini-privacy/

## Why this repo is public

WHOOP's app registration requires a **publicly reachable privacy-policy URL**, and its
review checks that the policy accurately describes what the app actually does. This repo
is that URL. **It must stay public** — if it goes private, GitHub Pages stops serving it
on the free plan and the URL dies, which blocks app approval.

## Why it contains only the policy

The Kombini application code lives in a **separate private repository**, because it is the
thing that touches personal health data (WHOOP recovery/HRV/sleep, self-reports, PVT
results, optional EEG/CGM). Keeping the policy and the engine in one repo forces a single
visibility decision onto two objects that need opposite ones — so they are split.

## Editing

`index.html` is the entire site. Push to `main` and GitHub Pages redeploys automatically
(takes ~1–2 minutes).

Two rules when editing:

1. **Keep it accurate.** If the app starts collecting a new category of data, add it here
   in the same change. An inaccurate policy is worse than no policy.
2. **Never put application code, credentials, or health data in this repo.** It is public.

## Related

- Engine (private): `felixpang625/kombini`
- Data-flow map that keeps this policy honest: `docs/DATA_FLOWS.md` in the engine repo.

## Not legal advice

This policy is a working draft maintained by the developer, not a lawyer.
