# claudemods

Claude Code mods as one plugin marketplace (needs Claude Code 2.1.287+).

```bash
claude plugin marketplace add PLALITHKUMARSUTHAR/claudemods
claude plugin install replay-theater@claudemods
claude plugin install savvy-progress@claudemods
claude plugin install terminal-browser@claudemods
claude plugin install reflect-mod@claudemods
```

- **replay-theater** (Anthropic sample): `/replay` steps through the last turn's edits.
- **savvy-progress** (JohnnyVizz/claude-kit): progress bar and `/agents-info` panel.
- **reflect-mod** (BayramAnnakov/claude-reflect): finds corrections in your prompts and saves them to CLAUDE.md. Uses a small model call per prompt. Do not also install the claude-reflect plugin (double capture).
- **terminal-browser** (zenbu-labs): `/browser`; needs the `terminal-browser` binary and a kitty-graphics terminal.

Mods are unsandboxed code; review before installing. Copies of upstream plugins, see each plugin's LICENSE/README.
