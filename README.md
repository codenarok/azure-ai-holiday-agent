# Azure AI Holiday Agent

This repository contains the configuration and Logic Apps for the Azure AI Holiday Agent.

## Structure

- `architecture/architecture.png`: Architecture diagram export from Draw.io.
- `logic-apps/`: Logic App workflow definitions.
  - `hotel-shop-checker.json`: Checks shops/restaurants around a hotel using Azure Maps.
  - `web-searcher.json`: Performs a web search using Google Custom Search.
- `agent-configuration/system-prompt.md`: System prompt configuration for the agent.
- `assets/`: Demo assets.
  - `demo-run.gif`: Screen recording of the playground.
  - `logic-app-success.png`: Proof of a successful Logic App run.

## Notes

All confidential values such as subscription IDs, resource groups, connection IDs, and secrets are redacted and replaced with placeholders.
