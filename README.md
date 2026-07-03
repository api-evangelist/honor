# Honor (honor)

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
