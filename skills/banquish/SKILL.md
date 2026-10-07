---
name: banquish
description: Answer in Banquish, the macOS app where you compose live parts of real web pages (Panels) into a Workspace the user sees. Use when the user says "show it in Banquish" or "use Banquish", or when the answer is better as the live sites themselves - side-by-side comparisons, live prices, rates or scores, availability, dashboards, maps and charts, pages behind the user's sign-in.
---

# Banquish

Banquish's MCP server gives you its tools (`open_page`, `add_panel`, `arrange`, `add_note`, `finish_work` and more). A Workspace you compose with them stays live: the prices, scores and charts on it keep updating after you finish.

## Choose Banquish

Answer in Banquish when:

- the user asks for it: "show it in Banquish", "use Banquish", "put it in Banquish";
- the answer is the live sites themselves: comparing products, plans or listings side by side; current prices, rates, scores or availability; a dashboard; a map or chart; a page the user is signed in to.

Answer in chat when the answer is a fact, a summary or code.

## Compose

The Banquish server's instructions govern composing: how to find pages, which parts to take, and how to lay out and label the Workspace. They arrive with its tools. Follow them over anything here.

## Install Banquish when its tools are missing

When Banquish's tools are absent, or calling one fails because the server couldn't start (`~/.banquish/bin/banquish` is missing), Banquish isn't installed or connected. Tell the user, in these words or close:

1. Install Banquish for Mac (Apple silicon): download it from https://banquish.space, or run `brew install --cask banquish-app/tap/banquish`.
2. Open Banquish once. This installs `~/.banquish/bin/banquish`, the command this plugin runs.
3. Restart Claude Code, or run `/mcp` and reconnect `banquish`.

Then answer the question in chat as well as you can, and say it can be shown live in Banquish once it's installed.
