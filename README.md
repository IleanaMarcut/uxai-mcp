# UX+AI MCP

101 practical UX and AI methods and 6 skills for researching, ideating, designing,
reviewing, and building products, served live to your AI. Created by
[Ileana Marcut](https://uxai.ileanamarcut.co) from years of hands-on UX and product
work, for paid subscribers of the
[UX+AI Newsletter](https://ileanamarcut.substack.com/).

- Site and catalog: [uxai.ileanamarcut.co](https://uxai.ileanamarcut.co)
- Newsletter: [ileanamarcut.substack.com](https://ileanamarcut.substack.com/)

## What it is

An MCP connector at `https://uxai.ileanamarcut.co/mcp`. Once connected, your AI can
search the method library, run any method on your own project, and install the skills.
The methods live on the connector, so every run uses the current version. Nothing to
download, nothing to keep up to date.

## How to connect

Sign-in is an email code: enter the email address your subscription is under, and a
6-digit code arrives by email. Access lasts 30 days, then you sign in again the same
way.

- **Claude (web, desktop, mobile)**: Settings, Connectors, add custom connector, paste
  the URL above.
- **Claude Code**: install the
  [UX+AI plugin](https://github.com/IleanaMarcut/uxai-mcp-plugin), which brings the
  connector with it. Run `/mcp`, pick `uxai`, sign in.
- **ChatGPT**: Settings, Connectors, add the URL. Works in normal chats through search
  and fetch; developer mode shows every tool.

## How to use it

Describe what you are working on, in plain words:

> Run a heuristic critique on this checkout screen
>
> I have interview notes, what are the themes?
>
> Check my project before it goes live

Your AI finds the right method, follows it on your material, and asks for what it
needs instead of guessing. You can also name a method directly, browse everything with
"what's in the UX+AI library?", or pick methods from your app's prompt menu where it
has one.

## How it works

Your AI talks to the connector through six tools:

| Tool | What it does |
|---|---|
| `search` | Finds methods and skills from plain words |
| `list_methods` | Lists the whole library: ids, titles, one-line summaries |
| `fetch` | Pulls one method's full text by id |
| `skills` | Lists the installable skills |
| `get_skill` | Returns a download link and install steps for one skill |
| `slash_commands` | Tells an AI how to install the Claude Code plugin |

Every method has a stable id, such as `heuristic-critique`. Download links from
`get_skill` work for 15 minutes and only for the person who asked. The methods flow
to signed-in subscribers only.

## The plugin, for Claude Code

[IleanaMarcut/uxai-mcp-plugin](https://github.com/IleanaMarcut/uxai-mcp-plugin) puts
the library one slash away: one command per method
(`/uxai:heuristic-critique our checkout screen`), `/uxai:methods` to browse,
`/uxai:skills` for the skills, and `/uxai:connect` to check your setup. The plugin
also installs the three workflow skills below.

## The skills

Six skills come with the subscription.

**For combining methods into workflows.** Describe your situation and the right one
steps in:

- **Project Health Check**: Check the health of a project you built: what breaks with real users, the security basics, and what to re-test after a change.
  Say: "project health check"
- **Portfolio Coach**: Build the portfolio case a hiring team will judge you by: positioning, a case study from a real project, and a tough critique aimed at the role.
  Say: "Portfolio Coach"
- **Agent Designer**: Design an AI agent or bot before it meets users: what it may do, when it hands off to a human, and its personality as a usable system prompt.
  Say: "Agent Designer"

**For specific needs.** Full packages that install once:

- **Idea Studio**: Dissects the concept under the brief and surfaces the tensions underneath.
  Ask: "install the Idea Studio skill"
- **AI UX Risk audit**: Find where your AI product could break trust, confuse people, or cause harm.
  Ask: "install the AI UX risk audit skill"
- **3D Studio**: Product-render-quality 3D elements for your site, from a sentence, a reference image, a sketch, or vector art.
  Ask: "install the 3D Studio skill"

Install any skill by asking: "install the 3D Studio skill". Your AI brings the
download link and the steps. In Claude Code, the three workflow skills arrive with the
plugin.

## The library

101 methods across 10 areas: research, ideation, flows and information architecture,
UX writing, critique and review, designing and building with AI, design systems,
designing AI products, productivity, and personal development.

The full list, with ids and one-line summaries: [docs/library.md](docs/library.md).
Or browse it on the site: [uxai.ileanamarcut.co](https://uxai.ileanamarcut.co).

## When something is off

- **New tools or skills don't show up**: start a new chat. If they still don't,
  disconnect and reconnect the MCP so your app picks up the new tools.
- **The library tools are missing entirely**: the account you signed in with is not on
  the subscriber list. If you subscribe, reconnect with the email address your
  subscription is under.
- **In Claude Code**: run `/uxai:connect`, which checks the setup and names the one
  thing to fix.
- **Anything else**: [ileana@creativegluelab.com](mailto:ileana@creativegluelab.com)

## Licence

The methods are licensed to individual subscribers for their own work. They flow to
signed-in subscribers only, and may not be redistributed or republished.

Copyright © 2026 Ileana Marcut, UX+AI. All rights reserved.
