# Chain Verify — VerifyAPI investor demo repository

This is the public, read-only target repository for Chain Verify's unauthenticated
`software_delivery` VerifyAPI demo endpoint (`POST /api/verify/demo`).

It exists so prospects can point a request at a real public repo when trying the
VerifyAPI demo without needing credentials.

**Current status:** the `software_delivery` evidence check (live GitHub commit/diff/PR
inspection) is not yet implemented in the API. A request against this repo today
returns a `needs_more_evidence` response indicating the external inspection provider
isn't configured yet — it does not read this repository's GitHub data. This README
will be updated once that integration ships.

See https://chainverify.org/verify-api for the product this demo will showcase.
