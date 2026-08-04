# Honor (honor)

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

Honor (Honor Technology, Inc.) is a San Francisco-based home care company, founded in 2014, that pairs a high-touch, non-medical in-home care network for aging adults with a proprietary technology and operations platform - the **Honor Care Platform**. The platform covers caregiver ("Care Pro") scheduling and matching, client care plans, visit management, and centralized back-office operations, and serves families across 800+ cities and towns in the United States.

In **August 2021, Honor acquired Home Instead**, the world's largest senior home care franchise network. Home Instead now operates as a subsidiary of Honor under the Home Instead name, and the Honor Care Platform powers both the Honor Care Network and Home Instead franchise offices. The combined organization represents one of the largest players in the home care industry.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/honor/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/honor/refs/heads/main/apis.yml)

## API Access Status: No Public API

As of this writing (2026-07-03), **Honor does not publish any public or partner developer API, developer portal, or API reference documentation.** The Honor Care Platform is a closed, first-party care-delivery operations system rather than an API product.

What exists is entirely first-party and app-facing, not an open developer surface:

- **Honor Care Pro** mobile app (iOS / Android) - Care Pros manage their schedule, choose shifts and clients, view client profiles and care needs, clock in/out, and record visit notes.
- **Honor Family** mobile app (iOS / Android) - families set up care visits, schedule times and locations, receive post-visit updates, and view wellness insights.
- **Client web portal** at `portal.honorcare.com` (login only).

These clients communicate with Honor's internal backend, but no endpoints, authentication scheme, OpenAPI definition, or partner-integration program is publicly documented. There is no `developer.joinhonor.com` / `developer.honorcare.com` developer portal.

> Disambiguation: `developer.honor.com` belongs to **HONOR**, the Chinese consumer-electronics / smartphone brand (formerly part of Huawei), and is unrelated to Honor Technology the home care company documented here.

Logical domains a Honor API *would* cover if one were ever published - Care Visits / Scheduling, Care Pros (caregivers), Clients, Care Plans, and Billing - are noted here only to describe the platform's shape. **No such endpoints are documented or modeled in this entry**, and none are fabricated. This repository is a stub kept for catalog completeness and will be updated if Honor ships a documented public or partner API.

## Pricing

Honor's pricing is **care-service based**, not API based. Costs are quoted per hour of in-home care (and vary by market, care needs, and hours), arranged through Honor or a local Home Instead office - there is no API product, usage tier, or metered API pricing to document.

## Tags

- Home Care
- Senior Care
- Aging
- Health Tech
- Care Platform
- Caregivers
- Home Instead
- No Public API

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## Common Properties

- [Website](https://www.joinhonor.com)
- [Website](https://www.honorcare.com)
- [LinkedIn](https://www.linkedin.com/company/joinhonor)
- [Crunchbase](https://www.crunchbase.com/organization/honor)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
