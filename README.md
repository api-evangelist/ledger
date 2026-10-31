# Ledger

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Ledger SAS is the Paris-headquartered maker of the Ledger hardware signer family (Nano, Flex, Stax) and the surrounding self-custody and institutional-custody platform. Its developer surface spans five distinct programs: the Ledger Wallet exchange-provider APIs (Swap, Buy, Sell, Earn and Card OpenAPI contracts an exchange partner implements so its service appears natively inside Ledger Wallet), the Ledger Enterprise "Vault API" for institutional custody — accounts, transactions, governance requests, whitelists, entities, staking, compliance digests and reporting/notification webhooks — the Ledger Enterprise Multisig transaction service for Ledger-secured Safe smart accounts, the Wallet API (a bi-directional JSON-RPC 2.0 bridge that lets a Live App talk to a Ledger signer), and the Device Management Kit plus Clear Signing stack for building native device apps and clear-signed transactions. Ledger also publishes an unusually complete agent surface for a hardware company: an RFC 9727 /.well-known/api-catalog, an llms.txt on the developer portal, and first-party Agent Skills for coding agents and the Ledger Wallet CLI.

**Areas:** Ledger · Cryptocurrency · Digital Assets · Hardware Wallet · Self-Custody · institutional-custody · Blockchain · Payments · Staking · Security · Agent Skills · Agent-Native

## Ledger on APIs.io

Everything profiled for Ledger is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ledger/](https://apis.io/providers/ledger/)** — or go straight to one of the APIs or properties below.

### APIs (42)

- [Ledger Wallet API](https://apis.io/apis/ledger/ledger-wallet-api/) — Bi-directional JSON-RPC 2.0 interface between a Live App (dApp) and a wallet implementing the Wallet API Server, such as Ledger Wallet. Currency-agnostic…
- [Ledger Device Management Kit](https://apis.io/apis/ledger/ledger-device-management-kit/) — TypeScript SDK for discovering, connecting to and driving Ledger hardware signers over WebHID, Bluetooth, USB and Speculos — sessions, device state, app…
- [Ledger Accounts API](https://apis.io/apis/ledger/ledger-accounts-api/) — The Accounts API from Ledger — 17 operation(s) for accounts.
- [Ledger Authentication API](https://apis.io/apis/ledger/ledger-authentication-api/) — The Authentication API from Ledger — 2 operation(s) for authentication.
- [Ledger Buy Redirect API](https://apis.io/apis/ledger/ledger-buy-redirect-api/) — The Buy Redirect API from Ledger — 1 operation(s) for buy redirect.
- [Ledger Capabilities API](https://apis.io/apis/ledger/ledger-capabilities-api/) — The Capabilities API from Ledger — 1 operation(s) for capabilities.
- [Ledger Cardano API](https://apis.io/apis/ledger/ledger-cardano-api/) — The Cardano API from Ledger — 4 operation(s) for cardano.
- [Ledger Compliance API](https://apis.io/apis/ledger/ledger-compliance-api/) — The Compliance API from Ledger — 2 operation(s) for compliance.
- [Ledger Crypto Currencies API](https://apis.io/apis/ledger/ledger-crypto-currencies-api/) — The Crypto Currencies API from Ledger — 1 operation(s) for crypto currencies.
- [Ledger Currencies API](https://apis.io/apis/ledger/ledger-currencies-api/) — The Currencies API from Ledger — 5 operation(s) for currencies.
- [Ledger Delegates API](https://apis.io/apis/ledger/ledger-delegates-api/) — The delegates API from Ledger — 2 operation(s) for delegates.
- [Ledger Digests API](https://apis.io/apis/ledger/ledger-digests-api/) — The Digests API from Ledger — 3 operation(s) for digests.
- [Ledger Entities API](https://apis.io/apis/ledger/ledger-entities-api/) — The Entities API from Ledger — 4 operation(s) for entities.
- [Ledger Ethereum API](https://apis.io/apis/ledger/ledger-ethereum-api/) — The Ethereum API from Ledger — 3 operation(s) for ethereum.
- [Ledger Groups API](https://apis.io/apis/ledger/ledger-groups-api/) — The Groups API from Ledger — 3 operation(s) for groups.
- [Ledger Grow API](https://apis.io/apis/ledger/ledger-grow-api/) — The Grow API from Ledger — 1 operation(s) for grow.
- [Ledger Labels API](https://apis.io/apis/ledger/ledger-labels-api/) — The Labels API from Ledger — 2 operation(s) for labels.
- [Ledger Messages API](https://apis.io/apis/ledger/ledger-messages-api/) — The Messages API from Ledger — 3 operation(s) for messages.
- [Ledger Modules API](https://apis.io/apis/ledger/ledger-modules-api/) — The modules API from Ledger — 1 operation(s) for modules.
- [Ledger Notifications API](https://apis.io/apis/ledger/ledger-notifications-api/) — The notification feature allows you to be notified when an API user receives an important event. To receive a webhook notification, you must first register…
- [Ledger Organizations API](https://apis.io/apis/ledger/ledger-organizations-api/) — The Organizations API from Ledger — 1 operation(s) for organizations.
- [Ledger Owners API](https://apis.io/apis/ledger/ledger-owners-api/) — The owners API from Ledger — 1 operation(s) for owners.
- [Ledger Pairs API](https://apis.io/apis/ledger/ledger-pairs-api/) — The Pairs API from Ledger — 1 operation(s) for pairs.
- [Ledger PKI API](https://apis.io/apis/ledger/ledger-pki-api/) — The PKI API from Ledger — 1 operation(s) for pki.
- [Ledger Pledges API](https://apis.io/apis/ledger/ledger-pledges-api/) — The Pledges API from Ledger — 2 operation(s) for pledges.
- [Ledger Quote API](https://apis.io/apis/ledger/ledger-quote-api/) — The Quote API from Ledger — 1 operation(s) for quote.
- [Ledger Requests API](https://apis.io/apis/ledger/ledger-requests-api/) — A Request represents the intent of creating or changing an object in the system. For example, when you create a transaction, a *Create transaction* request…
- [Ledger Safes API](https://apis.io/apis/ledger/ledger-safes-api/) — The safes API from Ledger — 6 operation(s) for safes.
- [Ledger Sell API](https://apis.io/apis/ledger/ledger-sell-api/) — The Sell API from Ledger — 1 operation(s) for sell.
- [Ledger Sell Redirect API](https://apis.io/apis/ledger/ledger-sell-redirect-api/) — The Sell Redirect API from Ledger — 1 operation(s) for sell redirect.
- [Ledger Settlements API](https://apis.io/apis/ledger/ledger-settlements-api/) — The Settlements API from Ledger — 4 operation(s) for settlements.
- [Ledger Solana API](https://apis.io/apis/ledger/ledger-solana-api/) — The Solana API from Ledger — 4 operation(s) for solana.
- [Ledger Stakes API](https://apis.io/apis/ledger/ledger-stakes-api/) — The Stakes API from Ledger — 1 operation(s) for stakes.
- [Ledger Status API](https://apis.io/apis/ledger/ledger-status-api/) — The Status API from Ledger — 1 operation(s) for status.
- [Ledger Swap API](https://apis.io/apis/ledger/ledger-swap-api/) — The Swap API from Ledger — 2 operation(s) for swap.
- [Ledger Tezos API](https://apis.io/apis/ledger/ledger-tezos-api/) — The Tezos API from Ledger — 2 operation(s) for tezos.
- [Ledger Transaction API](https://apis.io/apis/ledger/ledger-transaction-api/) — The Transaction API from Ledger — 1 operation(s) for transaction.
- [Ledger Transactions API](https://apis.io/apis/ledger/ledger-transactions-api/) — The transactions API from Ledger — 10 operation(s) for transactions.
- [Ledger Users API](https://apis.io/apis/ledger/ledger-users-api/) — The Users API from Ledger — 3 operation(s) for users.
- [Ledger Webhook API](https://apis.io/apis/ledger/ledger-webhook-api/) — The Webhook API from Ledger — 1 operation(s) for webhook.
- [Ledger Whitelists API](https://apis.io/apis/ledger/ledger-whitelists-api/) — The Whitelists API from Ledger — 3 operation(s) for whitelists.
- [Ledger Tx Service API](https://apis.io/apis/ledger/ledger-tx-service-api/) — The Tx Service API from Ledger — 5 operation(s) for tx service.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Ledger Exchange Webhooks](https://apis.io/asyncapis/ledger/ledger-exchange-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [ledger-mcp.yml](https://apis.io/servers/ledger/ledger-mcp-yml/)

#### Overlays (2)

OpenAPI overlays, including conversational phrasing for each operation.

- [Ledger Enterprise Vault Overlay](https://apis.io/overlays/ledger/ledger-enterprise-vault-overlay/)
- [Ledger Swap Provider Overlay](https://apis.io/overlays/ledger/ledger-swap-provider-overlay/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Ledger Authentication](https://apis.io/security/ledger/ledger-authentication/)
- [Ledger Domain Security](https://apis.io/security/ledger/ledger-domain-security/)
- [Ledger Trust Center](https://apis.io/security/ledger/ledger-trust-center/)
- [Ledger Vulnerability Disclosure](https://apis.io/security/ledger/ledger-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ledger Plans Pricing](https://apis.io/plans/ledger/ledger-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ledger Rate Limits](https://apis.io/rate-limits/ledger/ledger-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ledger.com/)
- [Documentation](https://developers.ledger.com/)
- [Getting started](https://developers.ledger.com/docs/device-app/getting-started)
- [API reference](https://help.enterprise.ledger.com/api-documentation/reference/api-reference)
- [Support](https://support.ledger.com/)
- [Changelog](https://developers.ledger.com/docs/news)
- [Blog](https://www.ledger.com/blog)
- [Security](https://donjon.ledger.com/bounty/)
- [Compliance](https://enterprise.ledger.com/about)
- [Terms of service](https://shop.ledger.com/pages/terms-and-conditions)
- [Privacy policy](https://www.ledger.com/privacy-policy)
- [GitHub](https://github.com/LedgerHQ)
- [Status](https://status.ledger.com/)

## API Evangelist rating

**Kin Score 59.0** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 55.4 |
| Contract governance | 4.5 |
| Operational transparency | 81.6 |
| Developer ergonomics | 85.7 |
| Access clarity | 43.4 |

**Agent readiness 40.7** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | mostly (partial credit) |

**Regulatory alignment 32.1** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ledger/](https://apis.io/providers/ledger/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Ledger: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ledger/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
