# Lovable setup

Use Snoooz MCP in Lovable to help users build apps and workflows around Snoooz email automation.

## MCP server URL

### Global / US

```text id="5zj6s8"
https://app.snoooz.ai/mcp
```

### EU

```text id="1cq5k9"
https://app-eu.snoooz.ai/mcp
```

## Suggested Lovable prompt

```text id="93nc5v"
Connect to Snoooz using MCP. Build an internal admin app that lets a manager:
- list Snoooz workspaces
- list mailbox automation health
- create AI reply rules
- configure automatic follow-ups
- preview replies before enabling automatic sending
- troubleshoot why a mailbox is not responding
```

## Example app ideas

```text id="ykdtzl"
Build a Snoooz setup wizard that asks the user about their sales and support workflow, then creates draft-only rules first.

Build a QA dashboard that lets users paste customer emails and preview how Snoooz would respond.

Build a rule-management console for admins to pause, update, or explain Snoooz rules.

Build a training dashboard where teams can add FAQs and search existing knowledge.
```

## Safety recommendation

When building user-facing workflows, prefer:

* Preview first
* Draft-only automation first
* Explicit confirmation before switching to auto-send
