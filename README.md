# LiveChat (livechat)

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
