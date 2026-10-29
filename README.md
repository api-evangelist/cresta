# Cresta

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

Cresta (legally Cresta Intelligence, Inc.) is a Palo Alto, California enterprise Customer Experience AI company spun out of the Stanford AI Lab and founded in 2017 by Zayd Enam, Tim Shi, and Sebastian Thrun, and led since 2023 by CEO Ping Wu, the former co-founder of Google Contact Center AI. The platform unifies human and AI agents for the enterprise contact center across voice, chat, email, and SMS, combining real-time agent assist, autonomous omnichannel AI agents, conversation intelligence, an AI analyst, a knowledge agent, coaching, a training simulator, and automated quality management, all orchestrated through Cresta Opera, a no-code AI orchestration layer, with Cresta Conductor as the developer facing agentic engine for building and optimizing AI agents. Cresta runs a multi-model architecture composed of 20+ large and small language models, fine-tuned on customer-specific transcripts and synthetic data, with enterprise guardrails, supervisory models, and automated pre-release AI agent testing. The AI Agent consumes external tools through API-based function calling and the Model Context Protocol; Cresta itself does not publish an MCP server. Voice integrations span Five9, Genesys (Cloud CX and Engage), NICE CXone, Amazon Connect, Twilio Flex, Talkdesk, 8x8, Vonage, Gladly, TCN, RingCX, Avaya Infinity, Cisco UCCE/PCCE/UCCX, and SIPREC across Oracle, Ribbon, Avaya SBC, and Cisco CUBE via SIP, PSTN transfer, CCaaS native streaming, WebSocket, gRPC, and raw RTP. Cresta is privately held at Series D with $280M+ raised from Greylock, Andreessen Horowitz, Sequoia, Tiger Global, Coatue, Greenoaks, Lightspeed, Porsche Ventures, World Innovation Lab, and the Qatar Investment Authority, plus strategic investors including Genesys, Five9, Accenture, Comcast, Qualcomm, JP Morgan, and Workday Ventures. It is the first Customer Experience AI provider to hold ISO/IEC 42001 certification, alongside SOC 2 Type II, ISO 27001, HIPAA, GDPR, TISAX, CCPA, and PCI DSS posture. A production API host is live at api.cresta.com — a gRPC-JSON transcoding gateway that answers anonymously with a google.rpc.Status error envelope — but the Cresta API and SDK are gated behind a customer / partner engagement: there is no public OpenAPI specification, no published API reference or base-path documentation, no public SDK release on any package registry, no public pricing, and no developer self-service signup.

**Areas:** Artificial Intelligence · Contact Center · Contact Center AI · CCaaS · Customer Experience · Conversational AI · Voice AI · Agent Assist · Conversation Intelligence · Knowledge Agent · Quality Management · Real-Time Coaching

## Cresta on APIs.io

Everything profiled for Cresta is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cresta/](https://apis.io/providers/cresta/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Cresta Platform API](https://apis.io/apis/cresta/cresta-platform-api/) — Cresta's production API host. https://api.cresta.com resolves and answers anonymously with a gRPC-JSON transcoding gateway error envelope…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cresta Context](https://apis.io/jsonld/cresta/cresta-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Cresta Contact Center AI Vocabulary](https://apis.io/vocabularies/cresta/cresta-vocabulary/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Cresta Domain Security](https://apis.io/security/cresta/cresta-domain-security/)
- [Cresta Trust Center](https://apis.io/security/cresta/cresta-trust-center/)
- [Cresta Vulnerability Disclosure](https://apis.io/security/cresta/cresta-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cresta Plans Pricing](https://apis.io/plans/cresta/cresta-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cresta Rate Limits](https://apis.io/rate-limits/cresta/cresta-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cresta.com)
- [Documentation](https://docs.cresta.com)
- [Support](https://cresta.com/contact-us)
- [Blog](https://cresta.com/blog)
- [Security](https://cresta.com/trust)
- [Trust centre](https://cresta.com/trust)
- [Terms of service](https://cresta.com/legal/terms-of-service)
- [Privacy policy](https://cresta.com/legal/privacy-policy)
- [GitHub](https://github.com/cresta)
- [Status](https://status.cresta.com)

## API Evangelist rating

**Kin Score 31.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 74.1 |
| Contract quality | 10.7 |
| Contract governance | 18.2 |
| Operational transparency | 28.9 |
| Developer ergonomics | 26.2 |
| Access clarity | 43.4 |

**Agent readiness 2.5** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 27.3** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cresta/](https://apis.io/providers/cresta/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cresta: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cresta/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
