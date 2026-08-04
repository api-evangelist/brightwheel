# Brightwheel (brightwheel)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Brightwheel ([mybrightwheel.com](https://mybrightwheel.com)) is an all-in-one childcare and early-education management platform used by childcare centers, preschools, and early-learning programs. It combines attendance and check-in, digital daily sheets, tuition billing and payments, enrollment and admissions, staff timecards, classroom (room) management, learning assessments, and real-time parent messaging with photo/video sharing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/brightwheel/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/brightwheel/refs/heads/main/apis.yml)

## API Access Model — No Public Developer API

> **Honest status:** As of this catalog entry (2026-07-03), Brightwheel does **not** publish a documented, self-serve public or partner developer API. This entry is an intentional stub. No API definitions, OpenAPI specs, plans, rate limits, or FinOps files are asserted, because none are publicly documented.

What the research confirmed:

- **No developer portal, no API reference, no API key or OAuth signup, no published OpenAPI/Swagger specification, and no webhook documentation** on mybrightwheel.com or in the [Brightwheel Help Center](https://help.mybrightwheel.com/en/).
- The only publicly acknowledged Brightwheel API work is **bespoke and contract-scoped**: a private API built for a specific government partner — **Iowa's childcare subsidy data system** — to submit attendance and subsidy data. This is a contract deliverable, not a documented public API. See [Government & Network Partners](https://mybrightwheel.com/government-and-network-partners/).
- Brightwheel also participates in **inbound integrations** where it pushes data into third-party SaaS — for example staff timecards to **Gusto** for payroll, and integrations with Birdeye (reviews) and airSlate SignNow (e-signature). These are partner-side integrations; they do not expose a Brightwheel API surface that outside developers can build against.
- The [Brightwheel GitHub organization](https://github.com/brightwheel) contains only third-party forks (Android UI libraries, Ruby/Docker tooling, MCP servers). There is **no first-party Brightwheel API client, SDK, or OpenAPI specification** published. Unofficial community `brightwheel-api` projects exist but are not official and are not backed by documented endpoints.

If you need to integrate with Brightwheel, the practical paths today are: (1) use the web app ([schools.mybrightwheel.com](https://schools.mybrightwheel.com)) and mobile apps, (2) rely on Brightwheel's pre-built third-party integrations, or (3) engage Brightwheel directly for a contract-scoped data integration (primarily available to government/network subsidy programs).

## Logical Product Areas (not documented APIs)

For reference only — these are the functional areas a Brightwheel API *would* cover if one were published. **No endpoints are documented or modeled here** (`endpointsModeled: none`):

- **Students / Children** — child profiles, enrollment, admissions
- **Attendance / Check-in** — check-in/out, digital daily sheets
- **Billing / Payments** — tuition plans, invoices, online bill pay
- **Staff** — teacher/admin profiles, timecards
- **Rooms** — classroom/room assignments and ratios
- **Parent Messaging** — real-time activity feed, messaging, photo/video sharing
- **Assessments** — learning/development assessments and reporting

## Tags

- Childcare
- Early Education
- Preschool
- Childcare Management
- Attendance
- Billing
- Payments
- Parent Communication
- EdTech
- No Public API

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## Pricing

Brightwheel does not publish prices publicly; pricing is **custom / quote-based per center**, typically reported in the range of roughly $3–$10 per child per month depending on tier and features, plus payment-processing fees on billing. There is no published API plan or developer tier. See [Brightwheel pricing](https://mybrightwheel.com/pricing/). No `plans/` file is included in this entry because there is no documented, sourced API pricing to model.

## Common Properties

- [Website](https://mybrightwheel.com)
- [Sign Up / Login](https://schools.mybrightwheel.com)
- [LinkedIn](https://www.linkedin.com/company/brightwheel)
- [GitHub Organization](https://github.com/brightwheel)
- [Documentation (Help Center)](https://help.mybrightwheel.com/en/)
- [Pricing](https://mybrightwheel.com/pricing/)
- [Government & Network Partners](https://mybrightwheel.com/government-and-network-partners/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
