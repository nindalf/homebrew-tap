# nindalf/tap

Homebrew casks for [Captain's Log](https://github.com/nindalf/CaptainsLog), a local work log for macOS.

```sh
brew install --cask nindalf/tap/captains-log
```

This installs the app, links the `captains-log` CLI onto your PATH, and links its skills into `~/.claude/skills` (Claude Code) and `~/.agents/skills` (Codex) for whichever is set up.

The cask is generated: edit `homebrew/captains-log.rb` in the [CaptainsLog repo](https://github.com/nindalf/CaptainsLog). `just release` sets its version and checksum and publishes it here.
