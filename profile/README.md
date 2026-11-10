<div align="center">

# Mudbase

**Backend-as-a-service for auth, databases, storage, realtime, wallets, and serverless functions.**

[Website](https://www.mudbase.dev) · [Docs](https://docs.mudbase.dev) · [Console](https://console.mudbase.dev) · [Pricing](https://www.mudbase.dev/pricing) · [LinkedIn](https://www.linkedin.com/company/mudbase-dev)

</div>

---

Mudbase gives you the pieces every backend needs, without running one yourself: authentication (email/password, OTP, magic link, OAuth, 2FA), a document database with row-level access rules, file storage, realtime subscriptions over WebSockets, serverless functions, non-custodial crypto wallets across 10+ chains, and KYC/compliance, all behind a single API and SDK.

## Repositories here

| Repo | What it is |
|---|---|
| [**mudbase-sdk**](https://github.com/mudbase/mudbase-sdk) | Official API clients for 9 languages: JavaScript/TypeScript, Python, Go, Ruby, Java, C#, PHP, Swift, and Dart/Flutter, generated from one shared OpenAPI spec. |
| [**mudbase-showcase-ecommerce**](https://github.com/mudbase/mudbase-showcase-ecommerce) | A complete ecommerce storefront (catalog, cart, checkout, orders, seller dashboard) built entirely on Mudbase, with no custom backend of its own. A reference for what a real production app on the platform looks like. |
| [**mudbase-showcase-social**](https://github.com/mudbase/mudbase-showcase-social) | A realtime social feed app (posts, likes, comments, live updates over WebSockets), built entirely on Mudbase. |
| [**mudbase-showcase-marketplace**](https://github.com/mudbase/mudbase-showcase-marketplace) | A two-sided marketplace app (listings, buyers, sellers, messaging) built entirely on Mudbase. |
| [**mudbase-showcase-kanban**](https://github.com/mudbase/mudbase-showcase-kanban) | A team task board (Kanban) app with boards, cards, and drag-and-drop, built entirely on Mudbase. |
| [**mudbase-showcase-events**](https://github.com/mudbase/mudbase-showcase-events) | An event listing and RSVP app built entirely on Mudbase. |
| [**mudbase-showcase-docs-search**](https://github.com/mudbase/mudbase-showcase-docs-search) | A documentation search app demonstrating full-text search on Mudbase. |

## Getting started

```bash
npm install mudbase-sdk
```

```ts
import { Configuration, AuthenticationApi } from "mudbase-sdk";

const config = new Configuration({
  basePath: "https://cloud.mudbase.dev",
  apiKey: process.env.MUDBASE_API_KEY,
});
```

Full quickstarts for every language: [docs.mudbase.dev/quickstart](https://docs.mudbase.dev/quickstart)

## Support

- Docs: [docs.mudbase.dev](https://docs.mudbase.dev)
- Issues on any repo above are welcome for SDK bugs and the demo app
- Platform support: [support@mudbase.dev](mailto:support@mudbase.dev)
- Follow us on [LinkedIn](https://www.linkedin.com/company/mudbase-dev)

Mudbase Inc, a Delaware corporation. 8 The Green, Ste A, Dover, DE 19901, USA.
