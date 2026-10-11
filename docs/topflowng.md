# TopFlowNG

**Live:** https://topflowng.com

TopFlowNG is a Nigerian digital-services platform for supported airtime, data, electricity, cable TV and related transaction workflows.

## Public product scope

The platform connects customer ordering, payment, provider fulfilment, transaction history, receipts, support and operational reconciliation in one self-service experience.

Supported service categories include airtime and data, utility payments, television subscriptions and other provider-backed digital services that are enabled in production.

## Public technology profile

Verified high-level technologies include:

- Node.js
- Express
- PostgreSQL
- Paystack integration
- External service-provider APIs
- Railway
- Redis-compatible caching/coordination
- Sentry-compatible monitoring
- Playwright and Node-based automated tests

## Reliability model

TopFlowNG treats a transaction as a workflow rather than a single button click: order state, payment state, provider response, fulfilment evidence and recovery paths are tracked separately so failures can be handled explicitly.

Provider credentials, payment secrets, customer data, internal reconciliation tooling and production environment values remain private.
