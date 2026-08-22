# Telefonie (telefonie)

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

Telefonie is a cloud communications platform providing programmable telephony, voice, SMS, and number management APIs for developers and businesses. The platform enables developers to build voice calling, SMS messaging, number provisioning, and call recording capabilities into their applications. Telefonie supports WebRTC, SIP trunking, and REST APIs for building modern communication workflows.

**APIs.json:** [https://www.telefonie.com](https://www.telefonie.com)

## Scope

- **Type:** Index

## Tags

- Call Recording
- CPaaS
- Messaging
- Number Provisioning
- SMS
- Telecommunications
- Telephony
- Voice
- VoIP

## Timestamps

- **Created:** 2024-01-20
- **Modified:** 2026-05-19

## APIs

### Telefonie Voice API

Make, receive, and control phone calls programmatically. Supports outbound dialing, inbound call handling, call routing, IVR (Interactive Voice Response), call transfer, conferencing, and real-time call control via REST and WebSockets.

- **Human URL:** [https://developers.telefonie.com/voice](https://developers.telefonie.com/voice)
- **Base URL:** `https://api.telefonie.com/v1/voice`

#### Tags

- Calls
- Conferencing
- IVR
- Outbound Calling
- Telephony
- Voice
- VoIP
- WebRTC

#### Properties

- [Documentation](https://developers.telefonie.com/voice)
- [OpenAPI](openapi/telefonie-voice-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefonie-voice.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonie-voice.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefonie.com/authentication)
- [Getting Started](https://developers.telefonie.com/getting-started)
- [Pricing](https://www.telefonie.com/pricing/voice)
- [Rate Limits](https://developers.telefonie.com/rate-limits)

### Telefonie SMS API

Send and receive SMS and MMS messages globally. Supports one-way notifications, two-way conversations, bulk messaging, unicode (international character sets), delivery receipts, inbound message webhooks, and long message concatenation.

- **Human URL:** [https://developers.telefonie.com/sms](https://developers.telefonie.com/sms)
- **Base URL:** `https://api.telefonie.com/v1/sms`

#### Tags

- Bulk SMS
- Delivery Receipts
- Messaging
- MMS
- SMS
- Text Messages
- Two-Way Messaging

#### Properties

- [Documentation](https://developers.telefonie.com/sms)
- [OpenAPI](openapi/telefonie-sms-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefonie-sms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonie-sms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefonie.com/authentication)
- [Pricing](https://www.telefonie.com/pricing/sms)
- [Rate Limits](https://developers.telefonie.com/rate-limits)

### Telefonie Number Management API

Search, purchase, configure, and manage phone numbers across multiple countries and number types (local, national, toll-free, mobile). Supports number portability (LNP), number lookup, capabilities checking, and configuring inbound call/SMS routing for numbers.

- **Human URL:** [https://developers.telefonie.com/numbers](https://developers.telefonie.com/numbers)
- **Base URL:** `https://api.telefonie.com/v1/numbers`

#### Tags

- DID
- LNP
- Number Portability
- Number Provisioning
- Phone Numbers
- Toll-Free

#### Properties

- [Documentation](https://developers.telefonie.com/numbers)
- [OpenAPI](openapi/telefonie-numbers-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefonie-numbers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonie-numbers.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefonie.com/authentication)
- [Pricing](https://www.telefonie.com/pricing/numbers)

### Telefonie Call Recording API

Record, store, and retrieve call recordings. Supports dual-channel recording, on-demand recording, automatic recording, transcription, storage management, compliance archiving, and secure download URLs. Recordings are stored in MP3 and WAV formats with configurable retention policies.

- **Human URL:** [https://developers.telefonie.com/recording](https://developers.telefonie.com/recording)
- **Base URL:** `https://api.telefonie.com/v1/recordings`

#### Tags

- Archiving
- Compliance
- Dual Channel
- Recording
- Storage
- Transcription

#### Properties

- [Documentation](https://developers.telefonie.com/recording)
- [OpenAPI](openapi/telefonie-recording-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefonie-recording.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefonie-recording.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefonie.com/authentication)
- [Pricing](https://www.telefonie.com/pricing/recording)

## Common Properties

- [Authentication](https://developers.telefonie.com/authentication)
- [Getting Started](https://developers.telefonie.com/getting-started)
- [Rate Limits](https://developers.telefonie.com/rate-limits)
- [S D Ks](https://www.telefonie.com/sdks)
- [Status Page](https://status.telefonie.com)
- [Terms of Service](https://www.telefonie.com/terms)
- [Privacy Policy](https://www.telefonie.com/privacy)
- [Sign Up](https://www.telefonie.com/signup)
- [Login](https://www.telefonie.com/login)
- [Blog](https://blog.telefonie.com)
- [Pricing](https://www.telefonie.com/pricing)
- [Changelog](https://developers.telefonie.com/changelog)
- [Git Hub](https://github.com/telefonie)

## Maintainers

**Email:** api@telefonie.com
**URL:** https://www.telefonie.com/team
