# agents

Plugins for coding agents.

```sh
claude plugin marketplace add hanneslipusch/agents
claude plugin install typeslop@hanneslipusch
```

| Plugin | What it does |
|---|---|
| [typeslop](https://github.com/hanneslipusch/typeslop) | A taste check for coding agents: a small judge reads every edit and sends the agent back once to fix the slop or say why it stays. |
| video-review | Turn recordings, screenshots and clips into a captioned review video and page. Private for now, so only its owner can install it. |

Each plugin lives in its own repository and releases by bumping its own version. Entries here carry no version and use `"source": "url"`, which Claude Code and Codex both read, so this catalog changes only when a plugin is added.
