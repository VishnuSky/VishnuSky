# Maintainer Checklist

## Manual Steps After PR Merges

### Profile page (`github.com/VishnuSky`)

- [ ] Create `VishnuSky/VishnuSky` repo and publish the contents of `README.md`
- [ ] Pin only `Legal-GPT` (unpin everything else)
- [ ] Bio: `Public legal literacy tools. Not a lawyer. Not legal advice.`
- [ ] Website: `https://x.ai/bot/4p9YXeUcvV7TeiErQvdIj`
- [ ] Location: `Washington, USA` (no street/school/workplace)
- [ ] X `@ixtly` already linked — leave as-is

### Legal-GPT repo settings

- [ ] About description: `Open-source legal literacy. Verified public law and service directories. Powers Public Law Scout on Grok. Not legal advice.`
- [ ] Homepage: `https://x.ai/bot/4p9YXeUcvV7TeiErQvdIj`
- [ ] Add these 8 topics:
  - `legal-tech`
  - `legal-literacy`
  - `open-source`
  - `cps`
  - `civil-rights`
  - `icwa`
  - `grok`
  - `mcp`
- [ ] License: if GitHub shows `Other` instead of MIT, verify the `LICENSE` file matches the standard MIT text and move any extra practice disclaimer outside the license body

### Stub repos

- [ ] Archive `JPT-Theory_in_Progress`
- [ ] Archive `Therapy-GPT`
- [ ] Archive `Nutritionist-GPT`
- [ ] Archive `Persona-GPT`
- [ ] Paste archived README into each (optional but cleaner)

### Branch cleanup

- [ ] Delete `feat/alpha-0.3.1-improvements` after confirming it was merged
- [ ] Delete `feat/alpha-0.3.2-readme-cli-training` after confirming it was merged
- [ ] Delete `feat/civil-service-core` after confirming it was merged
- [ ] Delete fully merged `copilot/*` branches

### Releases

- [ ] Do **not** tag `v1.0.0`
- [ ] Optional: tag `v0.3.3` on current `main` after the privacy fix merges
