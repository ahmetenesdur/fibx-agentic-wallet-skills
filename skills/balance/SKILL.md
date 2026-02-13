---
name: balance
description: Check wallet balance. Use when you or the user want to see funds, check ETH or token holdings.
user-invocable: true
disable-model-invocation: false
allowed-tools: ["Bash(fibx status*)", "Bash(fibx balance*)"]
---

# Checking Balance

Use the `fibx balance` command to check current holdings.

## Usage

```bash
fibx balance [--json]
```

## Examples

```bash
# Check balance
fibx balance

# Check balance as JSON
fibx balance --json
```
