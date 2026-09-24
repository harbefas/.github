<h1 align="center">Harbefas</h1>

<p align="center">
  Open-source replacements for tools that should never have been rented.<br>
  Terminal-first, keyboard-driven, no account required.
</p>

<p align="center">
  <a href="https://harbefas.github.io">harbefas.github.io</a>
</p>

---

The feed decides what you read. The library disappears when the licence lapses.
The assistant runs under rules written by the company that sells it. None of
that is a technical requirement — it is what happens when the tool belongs to a
vendor and you are the tenant.

This org takes one of those tools at a time and builds the version you can own:
read the source, run it offline, fork it if the maintainer goes quiet.
Sometimes that means a new program; often it means a patch to one that already
exists.

Small programs, one job each, MIT. Keyboard before mouse, terminal before tab,
plain text before database, local-first before cloud.

### Read, watch, listen

| Project | What it does | Replaces |
|---|---|---|
| [paperboy](https://github.com/harbefas/paperboy) | RSS reader and podcast player as your browser's new tab | the algorithmic feed |
| [paperboy-tui](https://github.com/harbefas/paperboy-tui) | The same reader in the terminal | a web app for reading text |
| [oikos](https://github.com/harbefas/oikos) | Self-hosted media and retro-gaming server, driven from the TV or your phone | a stack of streaming subscriptions |

### The desktop

| Project | What it does | Replaces |
|---|---|---|
| Amphora *(in development)* | Browser on CEF where dark mode, ad blocking and vim keys are the browser, not extensions | Chrome plus a pile of extensions |
| [gambito](https://github.com/harbefas/gambito) | Keyboard-first Lichess client for tiling desktops, with Stockfish analysis | playing chess in a browser tab |
| [hyprpad](https://github.com/harbefas/hyprpad) | Phone as keyboard, trackpad and media remote for Wayland, over the browser | a proprietary remote-control app |
| [keybinds-tui](https://github.com/harbefas/keybinds-tui) | Keybinding lookup parsed from the real configs, live Neovim included | a cheatsheet you forgot to update |

### Agent infrastructure

| Project | What it does | Replaces |
|---|---|---|
| [arbitus](https://github.com/harbefas/arbitus) | Security gateway for MCP tool calls: auth, allow/deny lists, payload filtering, human approval, audit log | vendor-side guardrails you cannot inspect |
| [agent-code-buddy](https://github.com/harbefas/agent-code-buddy) | Approval surface on your phone for an agent's writes, commands and API calls | letting an agent run unattended |
| [agent-memory](https://github.com/nfvelten/agent-memory) | MCP server for project memory across sessions, with staleness checks | context that dies with the session |

### Look and feel

[Mate Creations](https://harbefas.github.io/matecreations-site/) — Yerba Mate (dark) and Tererê (light).
Tokens authored in DTCG JSON, compiled with Style Dictionary, WCAG-checked in both
themes, shipped to [Neovim](https://github.com/harbefas/yerba-mate.nvim),
[VS Code](https://github.com/harbefas/vscode-yerba-mate),
[Obsidian](https://github.com/harbefas/obsidian-yerba-mate),
[Zen Browser](https://github.com/harbefas/zen-yerba-mate) and
[LibreWolf](https://github.com/harbefas/librewolf-yerba-mate) from one source.

---

<p align="center">
  Patches welcome, here or upstream. MIT throughout, no CLA.
</p>
