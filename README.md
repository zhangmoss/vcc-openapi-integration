# vcc-openapi-integration
AI-Native skill for integrating LianLian VCC OpenAPI — describe what you need in plain language, and get production-ready, signed-and-verified Java code for 20+ virtual credit card APIs in minutes.
# LianLian VCC OpenAPI Skill

> One sentence in, global virtual credit card integration out.

**AI-Native Payment Infrastructure** — the first conversational integration solution for the
LianLian VCC (Virtual Credit Card) OpenAPI. Skip the documentation maze and wire up the full
VCC flow in minutes, just by describing what you need.

## Why VCC Skill

| Traditional API integration | AI-Native VCC Skill |
| --- | --- |
| Read tens of thousands of words of API docs | Just describe your requirement in one sentence |
| Hand-write request signing & verification | Signing/verification built in automatically |
| Endless debugging of param formats & types | Params generated strictly to spec |
| Manually handle edge cases & NPEs | Production-grade NPE protection |
| Dig through error-code docs to debug | Automatic error diagnosis & feedback |
| Days to finish a basic integration | Full integration in ~15 min + ~5 min auto-acceptance |

## Key Capabilities

- 🧠 **Deep API semantics** — Built-in knowledge of the full VCC OpenAPI: parameter meanings,
  business rules, and constraints, not just template substitution.
- 🔐 **Enterprise security, built in** — Request signing, authentication, and response
  verification are embedded in the generated code. No need to understand the underlying protocol.
- 🛡️ **Production-grade code** — Required-field validation, NPE defense, logging, and error
  diagnostics. Not a demo — code you can ship.
- 🔌 **One-click Webhooks** — Generates a unified webhook receiver with signature verification,
  JSON parsing, and topic-based dispatch across 5 notification types.
- 📦 **Multi-card-product support** — Dynamic doc-discovery mechanism handles per-product
  parameter rules (G01, P01, etc.).
- ⚡ **Incremental integration** — Detects already-integrated endpoints, generates new ones on
  demand, and never overwrites existing code.

## How It Works

1. **Describe your need** — e.g. "Help me integrate the VCC apply-card and balance APIs."
2. **Provide credentials** — The skill guides you through Developer ID, Token, and RSA key pair;
   skipped items get placeholders.
3. **Get production-ready code** — Complete Java with signing/verification, NPE defense, and
   logging, compile-checked.

## Beyond Code Generation: It Gets You Connected

Most AI coding tools stop at "generating code" — debugging and integration testing are on you.
VCC Skill goes further: after generating code, it **auto-generates tests, runs them against the
sandbox, verifies the signature chain, and validates every endpoint** until everything passes.

- 🔧 Auto-generates executable tests for each integrated endpoint
- ▶️ Runs the full suite against the sandbox in ~5 minutes
- ✅ Diagnoses failures (credential / parameter / signature issues) and fixes them

## API Coverage (20+ endpoints)

- **Card** — apply, query detail, query CVV2, list, cancel, freeze/unfreeze, update limit
- **Balance** — query account balance, query fund flow
- **Transactions** — top-up, authorization, settlement queries
- **Webhook** — `CARD_STATUS_CHANGED`, `CARD_LIMIT_CHANGED`, `TOPUP_FINISHED`, `AUTH_EVENT`, `CARD_3DS_OTP`

## Who It's For

- **Backend developers** — Stop reading API docs; generate fully-signed Java and focus on business logic.
- **Enterprise tech teams** — Standardized code structure and security conventions; incremental adoption.
- **Cross-border e-commerce** — VCC for overseas ad spend, supplier payments, and platform settlement.
- **AI Agent developers** — Build payment-capable agents; integrates with AI IDEs like Cursor and Kiro.

## Contact

- Technical support: dev_support@lianlianpay.com
- Business inquiries: cps@lianlian.com

© 2026 LianLian Pay. All rights reserved.
