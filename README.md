# AI Whisperers Cooperative — Member Portal

Private member portal for the AI Whisperers Cooperative founding framework.

**Live URL:** https://framework.the-ai-whisperers.com

## Files

- `index.html` — landing page with links to the three views
- `framework.html` — interactive design map (14 sections, 8 patterns)
- `rollout.html` — interactive rollout timeline (6 phases)
- `proposal.html` — full text proposal (renders the markdown)
- `founding_framework_proposal.md` — source-of-truth markdown for the proposal
- `CNAME` — custom domain config for GitHub Pages
- `robots.txt` — blocks search engine indexing
- `.nojekyll` — disables Jekyll processing

## Privacy

This site is unlisted. URL is shared only with cooperative members. `robots.txt` blocks search engines and `<meta name="robots" content="noindex, nofollow">` is on every page.

The site is publicly accessible to anyone with the URL. If sensitive data lands here in the future, add Cloudflare Access or equivalent auth.

## Editing

To update the proposal text: edit `founding_framework_proposal.md` and commit. The proposal page renders the markdown live, no build step needed.

To update the framework map or rollout: edit the `sections` or `phases` array near the bottom of `framework.html` or `rollout.html`.

## Maintainers

Shannon Seaver (shannon@the-ai-whisperers.com)
Randy Smasal (randysmasal@liftteams.com)
