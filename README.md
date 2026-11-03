# PRBee

Your AI agent works through your pull requests while you do something else.

PRBee is a desktop app for Mac, Windows and Linux that runs the Claude Code or Codex CLI you already use
over your GitHub pull requests, on your own machine, within the hours and budget you set.

- **Reviews** your colleagues' PRs in a full checkout, at the depth you choose. Findings it cannot verify
  in the code are dropped, not posted.
- **Replies** to review threads on your own PRs with a commit and an answer in each thread.
- **Fixes** red builds, resolves conflicts and keeps branches current. Merges only when you turn that on.
- **Learns** from what your reviewers catch, and follows your `CLAUDE.md` and `AGENTS.md`.

No account, no telemetry: your code only goes to GitHub and your agent's provider.

```sh
curl -fsSL https://prbee.dev/install.sh | bash
```

Windows: `irm https://prbee.dev/install.ps1 | iex`

30 days free, then $5 a month. [prbee.dev](https://prbee.dev) · [Compare](https://prbee.dev/compare/) · [Support](https://prbee.dev/support/)
