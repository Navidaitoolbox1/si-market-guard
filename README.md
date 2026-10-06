# SI Market Guard

SI Market Guard is a skills-only OpenAI plugin for ChatGPT and Codex. It supports English, French, German, and Persian.

## What it does

- Reviews portfolio concentration and overlap
- Separates ordinary volatility from material risk
- Flags broad-market, sector, and company-specific risks
- Defines staged buy zones for a cash reserve
- Uses neutral posture labels: HOLD, AVOID ADDING, WATCH CLOSELY, and CONSIDER REDUCING

## What it does not do

- It does not guarantee returns or predict exact market tops or bottoms
- It does not execute trades
- It does not connect to a brokerage account or store a persistent portfolio
- It is not a substitute for professional investment advice

## Package

This repository is a portable Agent Plugins package. Its root plugin.json contains the OpenAI listing metadata and translated descriptions. The skill is bundled at skills/market-guard/SKILL.md. The package has no MCP server or external API key requirement; it uses live web or market-data tools only when the host provides them.

## Submit to the Plugins directory

The ZIP is the submission package. Upload it from the OpenAI Plugins dashboard, resolve the automated metadata and skill checks, submit it for review, and publish after approval. A public GitHub repository provides the source and does not itself publish the plugin to the directory.

See SUBMISSION_CHECKLIST.md for the current steps and STORE_COPY.md for translated listing text. TEST_CASES.md contains suggested manual checks for the skills-only package.

## License

All rights reserved. Public visibility of this repository does not grant reuse rights.
