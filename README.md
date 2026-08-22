# Pomelo Health (pomelo-health)

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

Pomelo Health (formerly Chronometriq, founded 2012, headquartered in Montreal with offices in Boston and Toronto) is a Canadian patient-engagement software company operating within the TELUS Health ecosystem. Its cloud platform helps medical clinics reduce no-shows and modernize the front-desk experience with online booking/e-booking, automated SMS/voice/email appointment reminders, digital intake eForms, telemedicine, secure two-way messaging, patient broadcasts, and a patient portal.

Pomelo ships as an EMR add-on that syncs with TELUS Health EMRs — Accuro, Medesync, and TELUS CHR — rather than as an open integration platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pomelo-health/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pomelo-health/refs/heads/main/apis.yml)

## API / FHIR Posture

As of this review (2026-07-24), Pomelo Health publishes **no public developer portal, no documented REST/OpenAPI, and no public HL7 FHIR CapabilityStatement or SMART-on-FHIR configuration**. `developer.pomelohealth.com` does not resolve, and no `api.` / `fhir.` / `docs.` developer subdomain or `/developers` path could be confirmed. Multiple independent sources confirm Pomelo does not offer an open third-party API; integrations are delivered through the underlying TELUS Health EMR partners, each of which exposes its own API (for example, the Accuro REST API). This repository is therefore an honest identity stub for a company with a gated, partner-only integration model.

## Home Market

- Canada (province-fragmented healthcare, coordinated federally by Canada Health Infoway / pan-Canadian FHIR)

## Tags

- Healthcare
- Canada
- Patient Engagement
- Telehealth
- Appointment Scheduling
- Patient Portal
- eForms
- EMR Integration
- TELUS Health
- Digital Health

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

None documented publicly. Product surface (online booking, appointment reminders, eForms/intake, telemedicine, secure messaging, patient portal) is delivered as an EMR add-on, not as a public API. No REST/OpenAPI or FHIR CapabilityStatement was harvested.

## Common Properties

- [Website](https://www.pomelohealth.com/)
- [Support](https://support.pomelohealth.io/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
