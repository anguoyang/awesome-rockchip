# Contributing

Thanks for helping keep this list alive and accurate.

## The pledge

Every pull request gets a **first response within 48 hours**: merged, commented, or changes requested. If that ever slips, open an issue and call it out.

## What gets in

- Directly relevant to Rockchip platforms (RK3588/3588S, RK3576, RK3566/3568, RV1106/1126, or Rockchip tooling in general).
- The link is live and points at the project's own home (official repo, docs, or product page) — not a mirror, re-upload, or aggregator copy.
- Active within the last 12 months, **or** a stable official baseline (vendor BSP, official documentation, reference driver) — say which when you propose it.
- Not already listed. Check first.

## What does not get in

- Paid placements. There are none, for anyone.
- Forks with no meaningful change over upstream.
- Projects that merely mention Rockchip in passing.
- Dead links, archived projects (unless historically essential and marked as archived), and link shorteners.

## Entry format

One line, in the matching section of both `README.md` and `README.zh.md`:

```markdown
- [Project Name](https://example.com) - One sentence describing what it does and why a Rockchip developer would use it.
```

- Keep the description to one sentence, factual, no marketing superlatives ("best", "fastest", "amazing").
- Order within a section is by usefulness to a newcomer, not by stars; maintainers may reorder on merge.
- Chinese descriptions in `README.zh.md` should say the same thing as the English ones — translated meaning, not translated hype.

## Link health

A GitHub Action checks all links weekly. Failures are filed as issues and fixed or removed in the monthly maintenance round. If you spot a dead link before the bot does, a PR fixing it is the fastest path.
