# Brightwheel (brightwheel)

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
