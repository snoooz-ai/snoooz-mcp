# Tools

Snoooz MCP exposes tools for email automation, training, previews, and troubleshooting.

Exact tool availability depends on the signed-in user's role and permissions.

## Workspace tools

Examples:

* List workspaces
* Select the current workspace
* Inspect workspace setup

## Mailbox tools

Examples:

* Get my mailbox
* List mailboxes in a workspace
* Check mailbox connection status
* Check mailbox authentication status
* Check whether Snoooz automation is operational
* Turn Snoooz automation on or off

## Rule tools

Examples:

* List rules
* List rules in plain English
* Get a specific rule
* Create an automation rule
* Update an automation rule
* Delete a rule
* Reorder rules
* Pause or unpause rules
* Configure automatic follow-ups

Rules can be used to:

* Send AI replies
* Create drafts for review
* Forward emails
* Add labels
* Move emails to labels
* Add signatures
* Use templates
* Use AI custom prompts
* Configure automatic follow-ups

## Follow-up tools

Snoooz supports rule-level automatic follow-ups.

Follow-ups can be configured for rules that draft or send replies.

Follow-up settings can include:

* Send or draft mode
* Number of days between follow-ups
* Flexible scheduling window
* Working-hours scheduling
* Custom follow-up instructions
* Maximum follow-up attempts
* Attachment behavior

## Preview tools

Examples:

* Simulate which rule would match an email
* Preview the reply Snoooz would generate

Preview tools do not send emails.

Use preview tools before relying on automatic sending.

## Training tools

Snoooz can be trained from imported content such as:

* FAQs
* PDFs
* CSVs
* Websites and webpages
* Help-center sources
* Zendesk
* Intercom
* Document360
* SharePoint

Training content is stored as knowledge that Snoooz can use when drafting replies.

## Runtime context

Snoooz may also consult connected systems at runtime while processing emails.

Examples may include:

* Salesforce
* HubSpot
* Odoo
* SAP
* Microsoft Dynamics
* Shopify
* WooCommerce

Runtime context is different from stored training knowledge.

Stored training is imported and embedded.

Runtime context is looked up when Snoooz processes an email and decides that connected business-system context is relevant.

## Diagnostics and AI awareness

Snoooz MCP can explain:

* How rules are evaluated
* Why a rule matched or did not match
* Why an email was blocked by an exclusion rule
* Whether training data may be too limited
* Whether a rule may produce generic drafts
* Whether mailbox automation is currently operational
