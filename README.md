# LiveChat (livechat)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

LiveChat is a customer service and live chat platform used by businesses to engage website visitors, run sales conversations, and route support tickets across agent teams. The Text Platform (which powers LiveChat) exposes a suite of REST APIs for chats, agents, customers, configuration, and reporting, with both Web API and RTM (real-time messaging) interfaces. Authentication uses OAuth 2.1 with Personal Access Tokens or full OAuth authorization code flow.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/livechat/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/livechat/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Live Chat
- Customer Service
- Customer Support
- Messaging
- Sales
- Help Desk

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### LiveChat Agent Chat API

REST and RTM APIs for agents to manage chats, send messages, transfer conversations, and update statuses. Authenticated with OAuth 2.1 bearer tokens or Personal Access Tokens.

- **Human URL:** [https://platform.text.com/docs/messaging/agent-chat-api](https://platform.text.com/docs/messaging/agent-chat-api)
- **Base URL:** `https://api.livechatinc.com/v3.5/agent`

#### Tags

- Agents
- Chats
- Messaging

#### Properties

- [Documentation](https://platform.text.com/docs/messaging/agent-chat-api)
- [Postman Collection](collections/livechat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livechat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LiveChat Customer Chat API

REST and RTM APIs for customers to start and participate in chats with agents on LiveChat-powered websites. Uses customer access tokens.

- **Human URL:** [https://platform.text.com/docs/messaging/customer-chat-api](https://platform.text.com/docs/messaging/customer-chat-api)
- **Base URL:** `https://api.livechatinc.com/v3.5/customer`

#### Tags

- Customers
- Chats
- Messaging

#### Properties

- [Documentation](https://platform.text.com/docs/messaging/customer-chat-api)
- [Postman Collection](collections/livechat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livechat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LiveChat Configuration API

Manage agents, groups, bots, tags, webhooks, properties, and other account configuration for a LiveChat organization.

- **Human URL:** [https://platform.text.com/docs/management/configuration-api](https://platform.text.com/docs/management/configuration-api)
- **Base URL:** `https://api.livechatinc.com/v3.5/configuration`

#### Tags

- Configuration
- Agents
- Webhooks
- Bots

#### Properties

- [Documentation](https://platform.text.com/docs/management/configuration-api)
- [Postman Collection](collections/livechat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livechat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LiveChat Webhooks and RTM API

Asynchronous event surfaces for LiveChat. HTTP webhooks registered through the Configuration API and the Agent Chat Real-Time Messaging (RTM) WebSocket API share the same event payloads (incoming_chat, incoming_event, chat_user_added, chat_user_removed, customer_updated, agent_*, bot_*, group_*, and more).

- **Human URL:** [https://platform.text.com/docs/messaging/agent-chat-api](https://platform.text.com/docs/messaging/agent-chat-api)
- **Base URL:** `wss://api.livechatinc.com/v3.5/agent/rtm/ws`

#### Tags

- Webhooks
- Real-Time Messaging
- WebSocket
- Events

#### Properties

- [Documentation](https://platform.text.com/docs/messaging/agent-chat-api)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/livechat/refs/heads/main/openapi/livechat-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/livechat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livechat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LiveChat Reports API

Retrieve reporting data for chats, agents, tags, and customer activity across the LiveChat organization.

- **Human URL:** [https://platform.text.com/docs/data-reporting/reports-api](https://platform.text.com/docs/data-reporting/reports-api)
- **Base URL:** `https://api.livechatinc.com/v3.5/reports`

#### Tags

- Reporting
- Analytics
- Metrics

#### Properties

- [Documentation](https://platform.text.com/docs/data-reporting/reports-api)
- [Postman Collection](collections/livechat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/livechat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/livechatcom)
- [Website](https://www.livechat.com)
- [Documentation](https://platform.text.com/docs)
- [Developer  Console](https://developers.livechat.com/console)
- [GitHub Organization](https://github.com/livechat)
- [Sign Up](https://accounts.livechat.com/signup)
- [Pricing](https://www.livechat.com/pricing/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
