# Replit setup

Use Snoooz MCP in Replit to help build tools that configure and inspect Snoooz email automation.

## MCP server URL

### Global / US

```text
https://app.snoooz.ai/mcp
```

### EU

```text
https://app-eu.snoooz.ai/mcp
```

## Suggested Replit prompt

```text
Use Snoooz MCP to build a small dashboard where a user can:
- select their Snoooz workspace
- list rules
- create a new AI reply rule
- configure follow-ups
- preview a reply
- check mailbox health
```

## Example workflows

```text
Create a support automation setup tool.

Create a lead response and follow-up rule generator.

Create a rule testing UI where users paste an email and see the matched rule and draft reply.
```

## Best practices

* Never store OAuth tokens in frontend code
* Use Snoooz OAuth flow through the MCP client
* Confirm destructive actions with users
* Preview replies before enabling auto-send behavior
