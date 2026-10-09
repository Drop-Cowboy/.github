## Drop Cowboy

**The Communication Platform Built Around Ringless Voicemail.**

Drop Cowboy gives you the tools to build voicemail, texting, calling, email and
AI voice agents into your own app or SaaS product: one API, one key, and
ready-made pieces you can drop into your own screens.

A ringless voicemail delivers your recorded message directly to the contact's
voicemail box.

### Start here: [Drop-Cowboy/dropcowboy](https://github.com/Drop-Cowboy/dropcowboy)

The developer hub repo has everything you need to start:

- A [one-file quickstart](https://github.com/Drop-Cowboy/dropcowboy/tree/main/examples/api/quickstart) that sends your first voicemail in about five minutes
- [Examples in Node.js, Python and C#](https://github.com/Drop-Cowboy/dropcowboy/tree/main/examples/api): send a voicemail, receive the result, manage webhooks
- A [sample CRM](https://github.com/Drop-Cowboy/dropcowboy/tree/main/examples/sample-crm) with calling, texting and contacts, to copy as the start of your own product
- [Skills](https://github.com/Drop-Cowboy/dropcowboy/tree/main/skills) an AI coding assistant reads to add a dialer, messenger, receptionist or voice tools to your app
- [Prompts](https://github.com/Drop-Cowboy/dropcowboy/blob/main/docs/vibe-coding.md) to paste into Cursor, Claude, ChatGPT or Lovable

```bash
git clone https://github.com/Drop-Cowboy/dropcowboy.git
```

### What you can build

Every piece is one API with one key.

- [Ringless voicemail](https://www.dropcowboy.com/developers/api/ringless-voicemail), with [proof of delivery](https://www.dropcowboy.com/developers/api/proof-of-delivery)
- [Texts, picture messages and RCS](https://www.dropcowboy.com/developers/api/texts)
- [Voice calls and voice broadcasts](https://www.dropcowboy.com/developers/api/voice-calls)
- [Email](https://www.dropcowboy.com/developers/api/email)
- [Bulk sends](https://www.dropcowboy.com/developers/api/campaigns) that go to a whole contact list
- [AI voice agents](https://www.dropcowboy.com/developers/api/agents) and an [AI receptionist](https://www.dropcowboy.com/developers/api/agents/ai-receptionist) that answers your number
- [Voicemail detection](https://www.dropcowboy.com/developers/api/detection): know if a person or a voicemail greeting picked up
- [Text to speech and voice cloning](https://www.dropcowboy.com/developers/api/voice)
- [Contacts, lists, consent and do-not-contact](https://www.dropcowboy.com/developers/api/contacts)
- [Two-way conversations](https://www.dropcowboy.com/developers/api/conversations)
- [Webhooks](https://www.dropcowboy.com/developers/api/webhooks) that tell your app what happened
- [Building Blocks](https://www.dropcowboy.com/developers/building-blocks): a dialer, messenger and receptionist you drop into your own app
- [Bring your own carrier](https://www.dropcowboy.com/developers/api/bring-your-own-carrier): send through your own phone company and numbers

### Docs and tools

- [Developer hub](https://www.dropcowboy.com/developers): every guide, and the [API quickstart](https://www.dropcowboy.com/developers/api/quickstart)
- [Every route on one page](https://www.dropcowboy.com/developers/api/quick-reference) and [result codes](https://www.dropcowboy.com/developers/api/outcomes)
- [OpenAPI spec](https://api-v2.dropcowboy.com/openapi.yaml), to generate a client in any language
- [Run in Postman](https://god.gw.postman.com/run-collection/5049225-40ae327c-2fd5-475d-a52c-fa9142609784?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D5049225-40ae327c-2fd5-475d-a52c-fa9142609784%26entityType%3Dcollection%26workspaceId%3D256b3e95-7b67-4783-9632-d59ca0a02803), or [read the collection on the web](https://documenter.getpostman.com/view/5049225/2sBYHPz21C)
- Build with an AI assistant: connect Cursor, Claude or VS Code to `https://mcp.dropcowboy.com/mcp` from **Connect AI** in the dashboard
- No code? [Automation](https://www.dropcowboy.com/automation) is built into every Drop Cowboy account. It connects Drop Cowboy to 700+ other apps, like HubSpot, Salesforce, Shopify, Calendly and Google Sheets. Open [**Automation**](https://www.dropcowboy.com/app/#/automation) in the dashboard's left menu to build a workflow

### Using the old v1 API?

It keeps working. The [`dropcowboy` npm package](https://www.npmjs.com/package/dropcowboy)
and its code live in [dropcowboy-cli](https://github.com/Drop-Cowboy/dropcowboy-cli).
New work should use the current API above, and the hub's
[`legacy/`](https://github.com/Drop-Cowboy/dropcowboy/tree/main/legacy) folder
shows how to move to it.

### Help

- support@dropcowboy.com
- [System status](https://status.dropcowboy.com)
