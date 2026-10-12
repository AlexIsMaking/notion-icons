# notion-icons

A Claude skill that gives Claude a complete reference of Notion's built-in icons and icon colours, so it always picks a name and colour that actually exist when it sets page icons through the Notion MCP tools.

Built by [aNotioneer](https://anotioneer.com).

## What it does

When Claude creates or updates a Notion page with a non-emoji icon, the skill:

1. Matches the concept to an icon from the full reference (629 icons across 7 categories).
2. Picks one of the 10 valid colours: `gray`, `lightgray`, `brown`, `yellow`, `orange`, `pink`, `blue`, `green`, `purple`, `red`.
3. Formats it as `:<icon-name>-<colour>:`, for example `:calendar-blue:` or `:rocket-orange:`.

If nothing fits, it falls back to a standard emoji.

## Install in Claude Code

```
claude plugin marketplace add AlexIsMaking/notion-icons
claude plugin install notion-icons@anotioneer
```

Or inside a session:

```
/plugin marketplace add AlexIsMaking/notion-icons
/plugin install notion-icons@anotioneer
```

## Use in Claude.ai

Download [`plugins/notion-icons/skills/notion-icons`](plugins/notion-icons/skills/notion-icons), zip the folder, and upload it as a skill in Claude's settings.

## Repo layout

```
.claude-plugin/marketplace.json                      marketplace catalogue
plugins/notion-icons/.claude-plugin/plugin.json      plugin manifest
plugins/notion-icons/skills/notion-icons/SKILL.md    the skill itself
```
