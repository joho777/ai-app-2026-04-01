# ToolTrust Studio

ToolTrust Studio is a single-file web app inspired by discussions around "fake tool" behavior in coding assistants (trend source: https://alex000kim.com/posts/2026-03-31-claude-code-source-leak/).

It helps you:
- Design AI tool schemas (args, limits, allowlist regex patterns, output keys)
- Toggle guardrails (receipts, strict JSON I/O, tool-shadowing block, undercover detection, frustration breaker)
- Compute an explainable risk score for susceptibility to tool-output fabrication
- Run a deterministic simulation (no model APIs) and export/share scenarios
- Generate a mitigation checklist and patch plan you can paste into engineering tickets

## Run locally

Just open `index.html` in a browser.

## Notes

- No backend and no external API calls.
- Uses Chart.js via CDN for the risk chart.

## Credits

- Trend/article: https://alex000kim.com/posts/2026-03-31-claude-code-source-leak/
