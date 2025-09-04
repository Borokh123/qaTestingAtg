TC-017 — HTTPS and secure auth cookies
Preconditions: Deployed over TLS
Steps: Perform successful login; inspect network/storage
Expected Result: HTTPS only; cookies flagged HttpOnly, Secure, SameSite (per policy)
Severity: Critical Priority: High Notes: Transport + cookie security