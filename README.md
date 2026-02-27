# cc-cost-check

Know what your AI costs per commit.

Interactive web calculator for Claude Code users. Input your plan and usage, or paste real session data from `cc-session-stats --json`.

**[Try it live](https://yurukusa.github.io/cc-cost-check/)**

## What it calculates

- **Cost per commit** — your AI's price tag per git commit
- **Cost per hour** — what you're paying for each hour of AI work
- **Cost per day** — daily cost on active days
- **Cost per session** — what each Claude Code session costs you
- **vs. alternatives** — compared to hiring a junior/senior dev, GitHub Copilot, ChatGPT Plus, Cursor

## Two modes

### Manual Input
Select your plan ($20 / $100 / $200 / custom), enter your weekly hours, commits, and active days.

### Real Data (cc-session-stats)
Run `npx cc-session-stats --json` and paste the output. The calculator extracts your actual usage patterns.

## Share your results
Generate a shareable summary with your cost breakdown. Post to X/Twitter or copy to clipboard.

## Part of cc-toolkit

| Tool | What it does |
|------|-------------|
| [cc-health-check](https://github.com/yurukusa/cc-health-check) | 20-check setup diagnostic |
| [cc-session-stats](https://github.com/yurukusa/cc-session-stats) | Usage analytics from session data |
| [cc-audit-log](https://github.com/yurukusa/cc-audit-log) | Human-readable audit trail |
| **cc-cost-check** | Cost per commit calculator |
| [cc-wrapped](https://yurukusa.github.io/cc-wrapped/) | Your AI year in review (Spotify Wrapped style) |

## Privacy

Zero tracking. No analytics. Everything runs in your browser. Your data never leaves your machine.

## License

MIT
