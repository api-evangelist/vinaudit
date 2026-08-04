# VINaudit

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

Vehicle history and VIN decoding REST API for accessing accident records, title information, mileage history, ownership records, and NHTSA recall data for any US vehicle. VINaudit is an NMVTIS-approved data provider founded in 2011, headquartered in Kirkland, Washington.

## APIs

- **Vehicle History API** - Raw vehicle history data from NMVTIS covering title records, odometer readings, accident records, salvage information, and theft records for US and Canada vehicles
- **Vehicle Specifications API** - Standardized vehicle specifications by VIN or YMMT including engine, transmission, fuel economy, dimensions, colors, equipment, recalls, warranties, and photos
- **Vehicle Market Value API** - Current market value estimates using aggregated data from millions of recent sale listings with low, average, and high-end values
- **Vehicle Ownership Cost API** - 5-year total cost of ownership calculations by VIN covering depreciation, insurance, fuel, maintenance, repairs, and taxes
- **Vehicle Image API (Beta)** - Original stock vehicle images by make, model, year, and trim

## API Endpoints

- `https://api.vinaudit.com/v2/query` - Query VIN records
- `https://api.vinaudit.com/v2/pullreport` - Generate vehicle history report
- `https://api.vinaudit.com/v2/report` - View generated report
- `https://specifications.vinaudit.com/v3/specifications` - Vehicle specifications
- `https://specifications.vinaudit.com/v3/selections` - Vehicle selections

## Authentication

API key-based authentication. Keys are generated from the VINaudit members dashboard after account registration. Pass the key as a `key` query parameter in all requests. A demo key (`VA_DEMO_KEY`) is available for testing.

## Links

- [Website](https://www.vinaudit.com)
- [Developer Guide](https://www.vinaudit.com/vin-api-developers-guide)
- [Vehicle Data API](https://www.vinaudit.com/vehicle-data-api)
- [Blog](https://www.vinaudit.com/blog)
- [LinkedIn](https://www.linkedin.com/company/vinaudit)
- [X / Twitter](https://twitter.com/vinauditllc)

## APIs.json

This repository contains an [APIs.json](apis.yml) index file cataloging VINaudit's public APIs, along with supporting documentation for pricing plans, rate limits, and FinOps guidance.
