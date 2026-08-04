# Zen Planner (zenplanner)

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

Zen Planner is gym, martial arts, yoga, affiliate, and fitness studio management software covering membership management, billing and payments, class scheduling, attendance and check-ins, skills/belt tracking, and a member app. **Zen Planner is owned by Daxko.** Its developer API is published on the shared **Daxko Partners** API platform as the "Zen Planner API."

**Access model:** The Zen Planner API is **partner-gated** - you request access through a Daxko sales representative and are provisioned OAuth 2.0 credentials. The API *reference* is publicly viewable (Daxko's Redocly-hosted docs), but calling the API requires a provisioned partner relationship, so live traffic was not exercised for this entry. The Classes endpoints are confirmed from the public reference; the remaining module operations are honestly modeled from the documented module set (`endpointsModeled: true`) and may differ in exact path, parameters, and payloads from the gated production surface.

**Base URL:** `https://api.partners.daxko.com/api/v1`
**Authentication:** OAuth 2.0 (partner tokens via `https://api.partners.daxko.com/v3/partners/oauth2/token`; member auth via `https://operations.oauth2.partners.daxko.com/token`)

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zenplanner/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zenplanner/refs/heads/main/apis.yml)

## Tags

- Fitness
- Gym Management
- Studio Management
- Martial Arts
- Membership
- Scheduling
- Class Booking
- Daxko

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## APIs

All APIs share the base URL `https://api.partners.daxko.com/api/v1` and are documented at the public Daxko Partners reference: [https://docs.partners.daxko.com/openapi/ZenPlanner/v1/](https://docs.partners.daxko.com/openapi/ZenPlanner/v1/)

### Zen Planner People API

Retrieve people (members and contacts) records held in a Zen Planner studio account. Person records are the anchor for memberships, class reservations, and attendance in the rest of the API.

- **Tags:** People, Members, Contacts
- **Properties:** [Documentation](https://docs.partners.daxko.com/openapi/ZenPlanner/v1/), [API Reference](https://docs.partners.daxko.com/openapi/ZenPlanner/v1/), [OpenAPI](openapi/zenplanner-openapi.yml)

### Zen Planner Memberships API

Access membership information for a person - the plans, agreements, and billing relationships that a member holds at a studio.

- **Tags:** Memberships, Billing, Subscriptions
- **Properties:** [API Reference](https://docs.partners.daxko.com/openapi/ZenPlanner/v1/), [OpenAPI](openapi/zenplanner-openapi.yml)

### Zen Planner Classes API

Retrieve class information including schedules and class types, list a person's class reservations, and list a person's class attendances (check-ins). Confirmed paths: `/classes`, `/classes/people/{personId}/reservations`, `/classes/people/{personId}/attendances`.

- **Tags:** Classes, Schedule, Reservations, Attendance
- **Properties:** [API Reference](https://docs.partners.daxko.com/openapi/ZenPlanner/v1/), [OpenAPI](openapi/zenplanner-openapi.yml)

### Zen Planner Locations API

Access information about the physical locations (studios) configured in a Zen Planner account.

- **Tags:** Locations, Studios
- **Properties:** [API Reference](https://docs.partners.daxko.com/openapi/ZenPlanner/v1/), [OpenAPI](openapi/zenplanner-openapi.yml)

### Zen Planner Programs API

Retrieve information about programs - the offerings (memberships, classes, services) a studio organizes its business around.

- **Tags:** Programs, Offerings
- **Properties:** [API Reference](https://docs.partners.daxko.com/openapi/ZenPlanner/v1/), [OpenAPI](openapi/zenplanner-openapi.yml)

### Zen Planner Prospects API

Create prospect (lead) records so external lead-capture and marketing tools can push new prospects into a studio's Zen Planner CRM.

- **Tags:** Prospects, Leads, CRM
- **Properties:** [API Reference](https://docs.partners.daxko.com/openapi/ZenPlanner/v1/), [OpenAPI](openapi/zenplanner-openapi.yml)

### Zen Planner Groups API

Access information about groups and the people associated with them - for example households or family memberships.

- **Tags:** Groups, Households, Memberships
- **Properties:** [API Reference](https://docs.partners.daxko.com/openapi/ZenPlanner/v1/), [OpenAPI](openapi/zenplanner-openapi.yml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/zenplanner)
- [Website](https://zenplanner.com/)
- [Documentation](https://docs.partners.daxko.com/openapi/ZenPlanner/v1/)
- [Plans](plans/zenplanner-plans-pricing.yml)

## Pricing

Zen Planner is priced as a monthly SaaS subscription scaled by **active members** (not staff or prospects). Public and third-party sources describe three editions from roughly **$99/month to ~$348/month**, with most studios paying $99-$200/month. See [plans/zenplanner-plans-pricing.yml](plans/zenplanner-plans-pricing.yml). API access is a separate, sales-gated Daxko Partners arrangement.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
