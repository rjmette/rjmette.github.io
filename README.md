# rjmette.github.io

This repository is the GitHub Pages site for `https://rjmette.github.io/`.

## Status: dormant

**Owner decision:** keep GitHub Pages dormant for now. Do not build a separate landing page here, and do not restore the removed AI project timeline. Once the personal site (`rjmette/personal-site`) is publicly live at a verified, stable URL, redirect this Pages site to that destination.

Redirect implementation is **deferred**. Completing this documentation ticket does **not** require deploying a redirect.

## GitHub Pages publishing source

Inspected via the GitHub Pages API (settings were not changed):

| Setting | Value |
| --- | --- |
| Status | built / enabled |
| Source branch | `master` |
| Source path | `/` (repository root) |
| Custom domain | none |
| Public URL | https://rjmette.github.io/ |

Every push to `master` publishes. The stale `main` branch still holds the old timeline files from issue #1; it is **not** the Pages source. Leave `main` alone.

## Related work

- **`rjmette/personal-site`** — intended long-term personal site. When it is live and its public URL is confirmed, this repo should redirect there. Do not guess or hard-code a destination before then.
- **Issue #1 (closed)** — AI story / project timeline index. That page was added and then removed from `master` because it was not ready to share. The dormant decision supersedes restoring it here; do not implement #1 as part of dormant-status documentation.

## Future redirect (deferred)

Prerequisite: `rjmette/personal-site` must be publicly reachable at a verified, stable URL.

When that prerequisite is met, a follow-up change can:

1. Confirm the live public URL of the personal site (do not invent one).
2. Add a redirect from this Pages site to that URL (for example a meta refresh / JavaScript location redirect in a minimal `index.html`, or whatever mechanism is chosen then).
3. Keep this README accurate about the new behavior.

No monitor or automation is scheduled by this ticket. No redirect should be published before the personal site is live.

## Public-repo hygiene

This repository is **public**. Do not commit personal details (phone numbers, employers, family names, email addresses, or similar). Keep content minimal while the site remains dormant.
