# Aeroseal

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

Aeroseal is a building-envelope and duct air-sealing technology company headquartered in Miamisburg, Ohio. Its patented aerosol sealing process — developed by Dr. Mark Modera under U.S. Department of Energy research at Lawrence Berkeley National Laboratory beginning in 1993 and commercialized as Aeroseal in 2010 — injects a fog of non-toxic sealant particles into a pressurized duct system or building envelope, where the particles collect at the edges of leaks and seal them from the inside. The company sells computer-controlled sealing equipment and software to a dealer network under the HomeSeal Connect and AeroBarrier Connect product lines.

- https://aeroseal.com/

## API surface

**None published.** As of 2026-08-06 Aeroseal publishes no public API, developer portal, SDK, or machine-readable specification. A live application backend exists at `https://api.aeroseal.com` — it answers the plain-text body `live (2.44)` at the root — but it serves the company's own connected sealing equipment and dealer software and returns HTTP 404 on every documented discovery path. See `x-coverage` in [apis.yml](apis.yml) and the full probe record in [well-known/aeroseal-well-known.yml](well-known/aeroseal-well-known.yml).
