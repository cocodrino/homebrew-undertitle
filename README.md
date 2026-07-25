# homebrew-undertitle

Homebrew tap for [Undertitle](https://github.com/cocodrino/undertitle) — an
on-device `.srt` subtitle generator for macOS (CLI + MCP server).

## Install

```bash
brew install --HEAD cocodrino/undertitle/undertitle
```

This builds from source (Xcode 26 + macOS 26 required), so the binaries are not
quarantined — no Gatekeeper prompt. You get two commands:

- `undertitle` — the command-line subtitle generator
- `undertitle-mcp` — an MCP server exposing a `transcribe_video` tool for agents
