# WELL Health Technologies (well-health)

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

WELL Health Technologies Corp (TSX: WELL, OTCQX: WHTCF) is a Vancouver, Canada-headquartered healthcare technology company — Canada's largest outpatient medical clinic owner-operator and a leading multi-disciplinary digital health service provider. It runs 115+ multidisciplinary clinics across Canada plus US telehealth and anesthesia operations, and a practitioner-enablement platform serving 44,000+ providers through the OSCAR Pro EMR, billing/revenue-cycle tools, eReferral, digital booking, and ePharma.

Its programmatic surface is the **apps.health** marketplace, through which third-party digital health apps integrate with WELL's network of EMRs (OSCAR Pro, Profile) using HL7 FHIR and other interoperability standards. As of this review there is no self-serve public developer portal, sandbox, OpenAPI, or FHIR CapabilityStatement — integration is FHIR-based but gated behind a partner/contact process. Home market is Canada, within a province-fragmented landscape coordinated federally by Canada Health Infoway's pan-Canadian FHIR (CA Core / CA Baseline) specifications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/well-health/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/well-health/refs/heads/main/apis.yml)

## Tags

- Healthcare
- Canada
- EMR
- EHR
- FHIR
- HL7
- Interoperability
- Digital Health
- Telehealth
- ePharma
- Clinics

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### apps.health EMR Integration (FHIR)

apps.health is WELL Health's digital health marketplace through which third-party apps integrate with WELL's network of EMRs (OSCAR Pro, Profile), which support HL7 FHIR and other interoperability standards. Integration is offered to vetted partners via a developer contact form; WELL supports the integration to its EMR network reaching 2,000+ clinics and 10,000+ healthcare professionals across Canada. No self-serve public API documentation, base URL, sandbox, or FHIR CapabilityStatement is published — the FHIR integration surface is gated behind a partner/contact process.

- **Human URL:** [https://apps.health/for-developers](https://apps.health/for-developers)

#### Tags

- Healthcare
- FHIR
- EMR
- Interoperability
- Canada

#### Properties

- [Documentation](https://apps.health/for-developers)
- [Website](https://apps.health/)

## Links

- [Website](https://well.company/)
- [Developer Portal (apps.health)](https://apps.health/for-developers)
- [Blog](https://well.company/blog)
- [Privacy Policy](https://well.company/privacy-policy/)
- [Terms of Service](https://apps.health/terms)
- [Support / Contact](https://well.company/contact/)
