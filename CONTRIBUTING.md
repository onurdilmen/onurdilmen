# Contributing

Hi 👋 — this repository hosts my GitHub profile README. It's primarily a
personal artifact, but if you spot a typo, broken link, or a way to make a
section render better, contributions are welcome.

## Quick wins (no permission needed)

- 🐛 **Found a typo or broken link?** Open an issue or a PR — both work
- 💡 **Have an idea for a section?** Open a Discussion (Q&A category)
- 🎨 **Spotted a layout glitch on a specific browser/theme?** Open an issue with a screenshot

## Working with the README

The README is generated **by hand**, not from a template. Key parts that update
automatically:

- `github-metrics.svg` — regenerated daily by `.github/workflows/metrics.yml`
  using [lowlighter/metrics](https://github.com/lowlighter/metrics)
- `github-snake-dark.svg` (on the `output` branch) — regenerated daily by
  `.github/workflows/snake.yml` using [Platane/snk](https://github.com/Platane/snk)

Both run automatically — no manual steps after merging changes.

## Pull request expectations

- One change per PR (typo fix ≠ layout change ≠ new section)
- Keep commits conventional (`fix:`, `feat:`, `docs:`, `chore:`)
- If you're adding a new external service (badge, image), make sure it returns
  HTTP 200 from a fresh request before opening the PR. Several services in this
  README have been replaced after going down (`github-readme-stats` Vercel,
  `streak-stats` Heroku) — we strongly prefer self-hosted SVGs

## Self-hosted vs external services

This profile **deliberately self-hosts** several SVGs (banner, metrics, snake,
screenshot placeholders) to avoid rate limits and 503s. When proposing a new
external service, please check:

1. Does it have a known uptime track record (years)?
2. Does it require an API token? (If yes, can we self-host instead?)
3. Does it adapt to GitHub's light/dark themes?

## Reporting security issues

Please don't open public issues for security findings — see
[SECURITY.md](SECURITY.md) for the private disclosure flow.

## Questions

Open a Discussion at [github.com/onurdilmen/onurdilmen/discussions](https://github.com/onurdilmen/onurdilmen/discussions)
or email me directly at onurdilmen@teknoweb.net.
