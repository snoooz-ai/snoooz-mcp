# OAuth and security

Snoooz MCP uses OAuth for authorization.

When an MCP-compatible app connects to Snoooz, you will be asked to sign in and approve access. The connecting app does not receive your Snoooz password.

## Discovery endpoints

### Global / US

```text
https://app.snoooz.ai/.well-known/oauth-protected-resource/mcp
https://app.snoooz.ai/.well-known/oauth-authorization-server
https://app.snoooz.ai/.well-known/openid-configuration
```

### EU

```text
https://app-eu.snoooz.ai/.well-known/oauth-protected-resource/mcp
https://app-eu.snoooz.ai/.well-known/oauth-authorization-server
https://app-eu.snoooz.ai/.well-known/openid-configuration
```

## OAuth endpoints

### Global / US

```text
https://app.snoooz.ai/oauth/register
https://app.snoooz.ai/oauth/authorize
https://app.snoooz.ai/oauth/token
https://app.snoooz.ai/oauth/jwks.json
https://app.snoooz.ai/oauth/userinfo
```

### EU

```text
https://app-eu.snoooz.ai/oauth/register
https://app-eu.snoooz.ai/oauth/authorize
https://app-eu.snoooz.ai/oauth/token
https://app-eu.snoooz.ai/oauth/jwks.json
https://app-eu.snoooz.ai/oauth/userinfo
```

## Permissions

Available tools depend on the scopes and role granted to the signed-in Snoooz user.

Some tools are read-only.

Some tools can update automation rules, training knowledge, templates, labels, mailbox settings, or follow-up configuration.

Destructive actions, such as deleting rules or training articles, should be confirmed by the user in the MCP client before execution.

## Security notes

Snoooz MCP should never expose:

* OAuth tokens
* Refresh tokens
* Mailbox credentials
* SMTP/IMAP passwords
* API keys
* Webhook secrets
* Internal system prompts
* Raw integration credentials

If you believe you found a security issue, see `SECURITY.md`.
