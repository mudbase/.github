<div align="center">

# Mudbase

**Backend-as-a-service for auth, databases, storage, realtime, wallets, and serverless functions.**

[Website](https://www.mudbase.dev) · [Docs](https://docs.mudbase.dev) · [Console](https://console.mudbase.dev) · [Pricing](https://www.mudbase.dev/pricing)

</div>

---

Mudbase gives you the pieces every backend needs, without running one yourself: authentication (email/password, OTP, magic link, OAuth, 2FA), a document database with row-level access rules, file storage, realtime subscriptions over WebSockets, serverless functions, non-custodial crypto wallets across 10+ chains, and KYC/compliance — all behind a single API and SDK.

## Repositories here

| Repo | What it is |
|---|---|
| [**mudbase-sdk**](https://github.com/mudbase/mudbase-sdk) | Official API clients for 9 languages — JavaScript/TypeScript, Python, Go, Ruby, Java, C#, PHP, Swift, and Dart/Flutter — generated from one shared OpenAPI spec. |
| [**mudbase-showcase-ecommerce**](https://github.com/mudbase/mudbase-showcase-ecommerce) | A complete ecommerce storefront (catalog, cart, checkout, orders, seller dashboard) built entirely on Mudbase, with no custom backend of its own. A reference for what a real production app on the platform looks like. |

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
