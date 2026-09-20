# Awesome iMessage

A curated list of tools, APIs, SDKs and resources for building on iMessage: business messaging platforms, developer clients, AI agent integrations and the research behind the blue bubble.

Maintained by [Blue Reacher](https://bluereacher.com). We build one of the platforms listed here, so the descriptions stick to what each vendor publishes and every entry earns its place on usefulness, not affiliation. PRs welcome; see the contributing note at the bottom.

## Contents

- [Business messaging platforms](#business-messaging-platforms)
- [Developer SDKs and clients](#developer-sdks-and-clients)
- [AI agents and MCP](#ai-agents-and-mcp)
- [Automation and no-code](#automation-and-no-code)
- [Apple official resources](#apple-official-resources)
- [Research and data](#research-and-data)

## Business messaging platforms

Platforms that let a business send and receive iMessage on dedicated or shared lines. Pricing and terms change monthly; check the vendor's page.

- [Sendblue](https://sendblue.com) - The category incumbent (Y Combinator S23). Inbound-first published tiers with a free sandbox; outbound is quoted through sales.
- [Blue Reacher](https://bluereacher.com) - Managed iMessage for B2B outbound: dedicated lines, campaigns built with you, CRM-native. Published pricing and a test-key simulator.
- [LoopMessage](https://loopmessage.com) - Developer API for two-way iMessage with opted-in contacts, plus Loop Lookup for availability checking.
- [Blooio](https://blooio.com) - Self-serve iMessage API with a flat pricing ladder and connectors for n8n, Make, Zapier and GoHighLevel.
- [Photon](https://photon.codes) - iMessage infrastructure for agent builders, with plainly published engineering terms.
- [Sendara](https://sendara.io) - CRM-first iMessage with native OAuth integrations for GoHighLevel, HubSpot, Close, Salesforce and Pipedrive.
- [Tuco AI](https://tuco.ai) - Budget warm-lead iMessage automation for opt-in and inbound leads, with plainly published caps.
- [Project Blue](https://tryprojectblue.com) - White-glove iMessage for GoHighLevel agencies, with sub-account reselling.
- [Linq](https://linqapp.com) - iMessage API for AI assistant companies, alongside the Linq Blue sales product.
- [Miss Blue](https://missblue.dev) - Shared team inbox plus an iMessage API.

## Developer SDKs and clients

- [bluereacher-node](https://github.com/Blue-Reacher/bluereacher-node) - Official TypeScript SDK for the Blue Reacher API. Typed end to end, zero runtime dependencies.
- [bluereacher-python](https://github.com/Blue-Reacher/bluereacher-python) - Official Python client for the Blue Reacher API.
- [bluereacher-cli](https://github.com/Blue-Reacher/bluereacher-cli) - Send iMessage from your terminal. Zero-dependency CLI.
- [bluereacher-openapi](https://github.com/Blue-Reacher/bluereacher-openapi) - Public OpenAPI 3.1 spec for the Blue Reacher API, browsable via Redoc.
- [bluereacher-examples](https://github.com/Blue-Reacher/bluereacher-examples) - Runnable recipes: lead reactivation, booking reminders, an AI coding agent iMessage channel.

## AI agents and MCP

- [bluereacher-mcp](https://github.com/Blue-Reacher/bluereacher-mcp) - Model Context Protocol server so AI agents (Claude, Cursor and any MCP client) can send iMessage and read replies.
- [Blue Reacher hosted MCP](https://docs.bluereacher.com) - The same MCP surface hosted at the API edge (`POST /v1/mcp`), no local server needed.

## Automation and no-code

- [n8n-nodes-bluereacher](https://github.com/Blue-Reacher/n8n-nodes-bluereacher) - n8n community node: send iMessage, check capability, manage contacts and opt-outs from workflows.
- [Zapier, Make and n8n connectors from Blooio](https://blooio.com) - Vendor-maintained connectors for the Blooio API.
- [GoHighLevel-native integrations](https://bluereacher.com/integrations) - Several platforms above (Blue Reacher, Sendara, Project Blue) run natively inside GoHighLevel workflows.

## Apple official resources

- [Messages for Business](https://register.apple.com/resources/messages/messaging-documentation/) - Apple's official program for businesses answering inbound customer chats through approved MSPs.
- [iMessage apps and stickers](https://developer.apple.com/imessage/) - Apple's developer surface for apps that run inside Messages.
- [Sending messages with Shortcuts](https://support.apple.com/guide/shortcuts/welcome/ios) - Personal-scale automation of Messages on your own device.

## Research and data

- [NBER Working Paper 33642](https://www.nber.org/papers/w33642) - Economics research measuring how much iPhone users value staying on iMessage rather than appearing as a green bubble.
- [DOJ v. Apple complaint (March 2024)](https://www.justice.gov/opa/pr/justice-department-sues-apple-monopolizing-smartphone-markets) - The antitrust filing whose messaging section documents the blue-versus-green dynamics.
- [State of iMessage for B2B](https://bluereacher.com/report/state-of-imessage-b2b) - Sourced statistics on reply rates, open rates and deliverability across channels.
- [Instantly Cold Email Benchmark](https://instantly.ai) - The most-cited cold email reply-rate baseline that iMessage numbers get compared against.

## Contributing

Open a PR. An entry needs to be publicly available, documented, and honestly described in one line; vendor self-submissions are fine if the description says what the product does rather than how good it is. Dead links and shut-down products get pruned.

## License

MIT
