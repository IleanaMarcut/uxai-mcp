# UX+AI MCP

The UX+AI MCP is a connector for your AI: 101 UX and AI methods and 6 skills by
[Ileana Marcut](https://uxai.ileanamarcut.co), served live to Claude, Claude Code, and
ChatGPT. This is its documentation.

- **URL**: `https://uxai.ileanamarcut.co/mcp`
- **What it serves**: 101 UX and AI methods, 6 skills, and resources such as the AI
  product principles
- **Who can use it**: paid subscribers of the
  [UX+AI Newsletter](https://ileanamarcut.substack.com/)

## Connecting

Add the URL as a custom connector in your AI app.

Sign-in is an email code: enter the email address your subscription is under, and a
6-digit code arrives by email. Access lasts 30 days, then you sign in again the same
way.

- **Claude (web, desktop, mobile)**: Settings, Connectors, add custom connector, paste
  the URL.
- **Claude Code**: install the
  [UX+AI plugin](https://github.com/IleanaMarcut/uxai-mcp-plugin), which brings the
  connector with it. Run `/mcp`, pick `uxai`, sign in.
- **ChatGPT**: Settings, Connectors, add the URL. Works in normal chats through search
  and fetch; developer mode shows every tool.

## The methods

101 methods across 10 areas: research, ideation, flows and information architecture,
UX writing, critique and review, designing and building with AI, design systems,
designing AI products, productivity, and personal development.

Ask for what you are doing in plain words and your AI finds the right one, or browse
the full catalog at [uxai.ileanamarcut.co](https://uxai.ileanamarcut.co). Methods are
served live: when one improves, your next run uses the new version.

## The skills

Six skills come with the subscription.

For combining methods into workflows:

- **Project Health Check**: where a build stands, ranked by what bites first
- **Portfolio Coach**: positioning, a case study from a real project, and a hard review
- **Agent Designer**: an agent's scope, handoff, and personality, decided on paper

For specific needs:

- **Idea Studio**: opens up an early idea before anything gets designed
- **AI UX Risk audit**: a structured risk report on an AI feature
- **3D Studio**: product-render 3D elements for your site, from a sentence or a sketch

Install any of them by asking: "install the 3D Studio skill". Your AI brings the
download link and the steps. In Claude Code, the three workflow skills arrive with the
plugin.

## The tools

What your AI can do once connected:

| Tool | What it does |
|---|---|
| `search` | Finds methods and skills from plain words |
| `list_methods` | Lists the whole library: ids, titles, one-line summaries |
| `fetch` | Pulls one method's full text by id |
| `skills` | Lists the installable skills |
| `get_skill` | Returns a download link and install steps for one skill |
| `slash_commands` | Tells an AI how to install the Claude Code plugin |

Every method has a stable id, such as `heuristic-critique`. Download links from
`get_skill` work for 15 minutes and only for the person who asked; ask again for a
fresh one.

## When something is off

- **New tools or skills don't show up**: start a new chat. If they still don't,
  disconnect and reconnect the MCP so your app picks up the new tools.
- **The library tools are missing entirely**: the account you signed in with is not on
  the subscriber list. If you subscribe, reconnect with the email address your
  subscription is under.
- **In Claude Code**: run `/uxai:connect`, which checks the setup and names the one
  thing to fix.
- **Anything else**: [ileana@creativegluelab.com](mailto:ileana@creativegluelab.com)

## What never leaves the connector

Method text is licensed to individual subscribers for their own work. It flows to
signed-in subscribers only, and may not be redistributed or republished.

Copyright © 2026 Ileana Marcut, UX+AI. All rights reserved.
