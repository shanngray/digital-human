# SECURITY STATUS: INACTIVE (classified 2026-11-09)

On 2026-11-09, Shannon Gray classified this repository as **inactive** for his own work. This is Shannon Gray's classification of his own use of the project. It is not an independent assessment of whether the code is maintained.

It **has known, unfixed security vulnerabilities** in its dependencies. Sentry's scan of 2026-11-09 (OSV, GitHub Advisory Database via OSV, CISA KEV) recorded 31 open advisories against this repository's default branch: 2 critical, 11 high, 15 medium, 2 low, 1 unknown.

Most serious (up to 5):
- langchain-core 0.2.7 (PyPI): GHSA-c67j-w6g6-q2cm / CVE-2025-68664, severity critical; fixed in 1.2.5, 0.3.81
- langchain-core 0.2.7 (PyPI): PYSEC-2026-373 / CVE-2025-68664, severity critical; fixed in 0.3.81, 1.2.5
- langchain-core 0.2.7 (PyPI): GHSA-pjwx-r37v-7724 / CVE-2026-44843, severity high; fixed in 1.3.3, 0.3.85
- langchain-core 0.2.7 (PyPI): PYSEC-2026-2564 / CVE-2026-44843, severity high; fixed in 0.3.85, 1.3.3
- langchain 0.2.5 (PyPI): PYSEC-2024-323 / CVE-2024-5998, severity high; fixed in 0.2.9

## Retained findings
Known findings for this repository are kept on record (Sentry's parked-findings list) and are not deleted while it is inactive.

## Before work resumes
1. Review the recorded findings and re-scan for newer advisories.
2. Remediate: update affected dependencies to fixed versions.
3. Test the project after the updates.
4. Then update or remove this file.

## Alerts while inactive
While this repository is inactive, Shannon gets a security alert only for **confirmed active exploitation**: a listing in the CISA Known Exploited Vulnerabilities catalog, OR reliable evidence of in-the-wild exploitation from another source (with source, URL and date). A public proof-of-concept or exploit code alone is not enough. Other advisories are kept on record without an alert.

## About this file
This file is a notice only. Placing it here does not guarantee that every person or tool reading the repository will see it. It does not replace or change any existing security policy: if a SECURITY.md exists in this repository, it still applies, so see [SECURITY.md](SECURITY.md) and report vulnerabilities as it describes.
