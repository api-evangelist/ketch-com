# Ketch (ketch-com)

Ketch is a San Francisco-based data permissioning and consent management platform — Ketch Switchbit — that helps enterprises keep customer data clean, permissioned, and AI-ready across web, mobile, and backend systems. The platform spans consent management, DSR automation, AI-powered data mapping, marketing preference management, risk and reporting, a Data Sentry privacy pentest, and an AI Governance layer. The Ketch Agent Network turns privacy program insights into agent-driven actions.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ketch-com/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- Privacy, Consent, Data Permissioning, DSR, Data Mapping, AI Governance, Preference Management, Risk, GDPR, CCPA, CPRA, Switchbit

## APIs
- **Ketch Platform API** — REST API at https://global.ketchapi.com powering consent, DSR, data mapping, preference, and risk endpoints. Authenticated via Harbormaster OAuth and API keys. Docs: https://docs.ketch.com/ketch/reference
- **Ketch Web SDK** — TypeScript/JavaScript Web API and consent library across the [github.com/ketch-sdk](https://github.com/ketch-sdk) org (`ketch-web-api`, `ketch-consent`, `ketch-types`, `ketch-data-layer`, `ketch-logging`).
- **Ketch Mobile SDKs** — Native iOS ([ketch-ios](https://github.com/ketch-com/ketch-ios)), Android ([ketch-android](https://github.com/ketch-com/ketch-android)), and React Native ([ketch-react-native](https://github.com/ketch-com/ketch-react-native)) SDKs plus a CocoaPods wrapper example.
- **Ketch Event Forwarders** — Server-side event forwarder spec with Go, Java, and Node/Express reference implementations under [github.com/ketch-com](https://github.com/ketch-com).
- **Ketch CLI** — Go-based [ketch-cli](https://github.com/ketch-com/ketch-cli) for developer workflows.
- **Ketch Tag Manager Templates** — [gtm-consent-mode](https://github.com/ketch-com/gtm-consent-mode) and [tealium-consent-template](https://github.com/ketch-com/tealium-consent-template).

## Timestamps
- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Common Properties
- [Website](https://www.ketch.com/)
- [Documentation](https://docs.ketch.com/)
- [API Reference](https://docs.ketch.com/ketch/reference)
- [Integrations](https://www.ketch.com/integrations) — 1,000+ pre-built integrations across analytics, CRM, CDP, ecommerce, marketing, tag management, and warehouses.
- [Pricing](https://www.ketch.com/pricing)
- [Status](https://status.ketch.com/)
- [GitHub: ketch-com](https://github.com/ketch-com)
- [GitHub: ketch-sdk](https://github.com/ketch-sdk)
- [Plans](plans/ketch-com-plans-pricing.yml) — Free / Starter ($150/mo) / Plus ($499/mo annual) / Pro / Enterprise. Metering driven by monthly unique users seeing the consent experience plus integration count.
- [RateLimits](rate-limits/ketch-com-rate-limits.yml) — request-rate limits are not publicly documented; quota is governed by the plan's monthly unique-user allowance.
- [FinOps](finops/ketch-com-finops.yml) — FOCUS-aligned subscription, primary unit `unique_user_month`; secondary units integration, dsr_request, property.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
