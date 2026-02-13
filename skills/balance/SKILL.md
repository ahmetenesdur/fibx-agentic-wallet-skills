---
name: balance
description: Check wallet balance. Use when you or the user want to see funds, check ETH or token holdings.
user-invocable: true
disable-model-invocation: false
allowed-tools: ["Bash(npx fibx status*)", "Bash(npx fibx balance*)"]
---

# Checking Balance

Use the `fibx balance` command to check current holdings.

## Usage

```bash
npx fibx balance [--json]
```

## Examples

```bash
# Check balance
npx fibx balance

# Check balance as JSON
npx fibx balance --json
```
