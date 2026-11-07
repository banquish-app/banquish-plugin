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

## Set up Banquish when its tools are missing

This plugin reaches Banquish through its Relay at `https://mcp.banquish.space/mcp`, which passes your calls to the Banquish app on the user's Mac. When Banquish's tools are absent, or a call says it needs sign-in, Banquish isn't installed or isn't paired yet. Tell the user, in these words or close:

1. Install Banquish for Mac (Apple silicon, macOS 13 or later): download it from https://banquish.space, or run `brew install --cask banquish-app/tap/banquish`. Open it, and keep it open while you use it.
2. In Claude Code, run `/mcp`, choose `banquish` and then Authenticate. A Banquish page opens in the browser and asks for a code.
3. In Banquish, choose File › Connect Claude…. Type the pairing code it shows into that page, then choose Pair.

When a call says Banquish can't be reached, the Mac is asleep or Banquish is closed: ask the user to open Banquish and try again.

Then answer the question in chat as well as you can, and say it can be shown live in Banquish once it's set up.
