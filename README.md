
# SubPilot API

Rust backend for SubPilot, a subscription-based SaaS integration prototype.

## Technology

- Rust
- Axum
- Supabase PostgreSQL
- Supabase Auth
- Stripe Billing

## Responsibilities

- Authenticate requests using Supabase JWTs.
- Manage subscription checkout through Stripe.
- Process Stripe webhooks.
- Enforce subscription-based application access.
- Provide user-scoped API operations.

## Development

```bash
cargo run
```

Health endpoint:

```text
GET /health
```

## Status

Under active development.
