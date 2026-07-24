# Pomelo Health (pomelo-health)

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
