# Troubleshooting

## The MCP client cannot connect

Check that you are using the correct regional endpoint.

### Global / US

```text
https://app.snoooz.ai/mcp
```

### EU

```text
https://app-eu.snoooz.ai/mcp
```

Make sure the endpoint includes `/mcp`.

## OAuth sign-in does not work

Confirm that your Snoooz account is in the same region as the MCP endpoint.

If you normally sign in at `app-eu.snoooz.ai`, use:

```text
https://app-eu.snoooz.ai/mcp
```

If you normally sign in at `app.snoooz.ai`, use:

```text
https://app.snoooz.ai/mcp
```

## I do not see all tools

Tool availability depends on the signed-in user's role and permissions.

For example, a normal mailbox user may see fewer tools than a workspace admin or company admin.

## Snoooz did not send a reply

Ask your MCP assistant:

```text
Check my mailbox troubleshooting status.

Explain why this test email did or did not match a Snoooz rule.

Preview the reply Snoooz would generate for this email.
```

Possible reasons include:

* Snoooz automation is not enabled
* The mailbox is disconnected
* Mailbox authentication expired
* The selected rule is paused
* No include rule matched
* An exclusion rule matched
* The rule is draft-only
* The account has no email credits
* A duplicate reply prevention rule blocked sending
* The message was not addressed to the mailbox owner
* Calendar or working-hours conditions blocked the rule

## Follow-ups are not running

Check:

* The selected rule has `followUp.enabled = true`
* The rule action is `sendEmail` or `draftEmail`
* The rule is not paused
* The original conversation qualifies for follow-up
* The recipient has not already replied
* Working-hours settings allow the follow-up
* The account plan supports follow-ups

## Need help?

Contact Snoooz support from inside the Snoooz app.
