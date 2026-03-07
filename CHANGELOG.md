# Changelog

## Unreleased
- Network hardening (client-side only): HTTPS-only transport, redirects disabled, and optional host allowlist + public key pinning to reduce the risk of traffic redirection or man-in-the-middle interception.
- Integrity checks: `.text` integrity and page-protection checks, plus non-executable page checks for `.data` and `.rdata` to help detect tampering (transparent, no stealth behavior).

## Notes
- These protections are defensive and transparent; they do not alter the backend or API and are intended to reduce common redirection and tampering risks.
