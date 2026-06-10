# scoop-bucket

Personal [Scoop](https://scoop.sh) bucket for [hyeonbungi](https://github.com/hyeonbungi)'s tools.

## Usage

```powershell
scoop bucket add hyeonbungi https://github.com/hyeonbungi/scoop-bucket
scoop install sync-ai-clis
```

## Apps

| App | Description |
| --- | --- |
| `sync-ai-clis` | Detect, install, and keep up to date multiple AI coding CLIs (Claude Code, Codex, Gemini, Kiro, Antigravity) with one command |

Manifests live in `bucket/` and track GitHub releases automatically via `checkver`/`autoupdate`. The `sync-ai-clis` manifest lands with its first public release (v0.1.0).
