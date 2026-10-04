# Technical Whitepaper — API

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/openreferral/api
**Category:** POLICE_CIVIC

## Abstract

This whitepaper describes the Anticloud integration of `API` (Social services data standard/API for civic use)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local NLP for report drafting — air-gapped, no cloud
2. AIOSS tamper-evident chain of custody log for all evidence and case records
3. AES-256 encryption for all personally identifiable information (PII)
4. Single-binary deployment on locked-down Windows/Linux police workstations
5. Offline facial recognition matching against local encrypted database only
6. Zero-cloud architecture: removes all third-party API dependencies
7. Audit trail for every record access and modification (GDPR/CCPA aligned)
8. Biometric auth integration without cloud identity providers

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.