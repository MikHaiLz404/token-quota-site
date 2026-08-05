# Token Quota — support and privacy site

The two pages the Mac App Store listing points at, served by GitHub Pages:

| Page | URL |
|---|---|
| Support | `https://mikhailz404.github.io/token-quota-site/` |
| Privacy Policy | `https://mikhailz404.github.io/token-quota-site/privacy.html` |

Static HTML and one stylesheet. No build step, no JavaScript, no third-party requests, no cookies,
no analytics — a privacy policy that loaded a tracker would be an awkward document.

The wording here is generated from the app's submission package,
`docs/app-review/privacy-and-app-review-package.md` in the (private) Token Quota repository. **Edit
that document first, then mirror the change here**, so the policy served to users and the policy
submitted to App Review cannot drift apart.

Both pages are deliberately claim-for-claim traceable to app behavior. Before changing a factual
sentence — what is stored, where, what is sent — confirm the behavior in the app first.
