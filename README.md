# Strange Works Studio — public policies

Public policy pages for games published by Strange Works Studio, served by
GitHub Pages because Google Play requires a privacy policy at a public HTTPS
URL and the game repositories are private.

| Page | URL |
| --- | --- |
| Breaker privacy policy | https://ashaver12.github.io/strangeworks-legal/privacy.html |
| Rogue Chess privacy policy | https://ashaver12.github.io/strangeworks-legal/rogue-chess-privacy.html |

## Editing

`privacy.html` is the source of truth for the published page. A copy lives at
`docs/privacy.html` in the Breaker repository so the policy travels with the
code that it describes. **Change both, together.** If they disagree, the page
served from here is the one players and Google see.

Update the effective date at the top of the page whenever the content changes.
Google Play expects the policy to describe the app as it actually ships, so the
policy is updated *before* the release that changes behaviour, not after.

Pushing to `master` republishes the site within a minute or two.

`rogue-chess-privacy.html` is the published Rogue Chess policy. Its working draft and submission notes
live at `store/PRIVACY_DRAFT.md` in the Rogue Chess repository. Change both, together.
