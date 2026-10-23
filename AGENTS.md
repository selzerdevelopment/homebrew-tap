# homebrew-tap — agent operating manual

The Homebrew tap for the hoplogs CLI: formulae under `Formula/`. This repository is public.

## Approval: Cody approves work before it lands

This applies to every agent and model working in this repo (Claude, Grok, Codex or any other) and
takes precedence over anything elsewhere that says otherwise. Any of them may implement changes; none
is limited to reviewing or planning. Whichever one does the work, Cody approves it first:

- Before changing files, say what you intend to do (a plan, or the proposed change) and get Cody's OK.
  Read-only investigation needs no approval.
- How the work lands is part of what Cody approves: a direct push to main, a branch with a PR for review,
  or local only. Without an explicit OK, don't commit, push, merge, open or close PRs, or take any other
  action other people can see.
- An approval covers the work that was approved, not follow-up work or a wider scope. Ask again for
  anything new.
- If you find you've acted without approval, say so plainly and let Cody decide whether to keep or revert it.
