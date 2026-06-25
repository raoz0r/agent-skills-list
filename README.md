# Agent Skills List
A public registry tracking official agent skills, their current versions, and their installation commands.

## How it Works
This repository contains a single `skills.json` file. An automated script runs weekly to check official sources and the GitHub API for updates, updating the last updated week data accordingly.

## Usage
You can access the raw data directly at this URL:
https://raw.githubusercontent.com/raoz0r/agent-skills-list/main/skills.json

## Data Format
The JSON file is structured as an array of objects:

```json
[
  {
    "name": "analyzing-financial-statements",
    "owner": "anthropics",
    "repo": "anthropic-cookbook",
    "version": "2026.26",
    "installCommand": "npx skills add [https://github.com/anthropics/anthropic-cookbook](https://github.com/anthropics/anthropic-cookbook) --skill analyzing-financial-statements"
  },
  {
    "name": "applying-brand-guidelines",
    "owner": "anthropics",
    "repo": "anthropic-cookbook",
    "version": "2026.26",
    "installCommand": "npx skills add [https://github.com/anthropics/anthropic-cookbook](https://github.com/anthropics/anthropic-cookbook) --skill applying-brand-guidelines"
  }
]
```
