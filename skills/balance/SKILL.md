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
npx fibx balance [--chain <chain>] [--json]
```

## Options

| Option              | Description                                            |
| ------------------- | ------------------------------------------------------ |
| `--chain <network>` | Specify network: `base`, `citrea`, `hyperevm`, `monad` |
| `--json`            | Output result as JSON                                  |

## Examples

```bash
# Check balance on Base (default)
npx fibx balance

# Check balance on Monad
npx fibx balance --chain monad

# Check balance as JSON
npx fibx balance --json
```
