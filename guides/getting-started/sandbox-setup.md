---
description: "How a partner gets a clean sandbox implementation environment."
icon: flask
---

# Sandbox setup

## What a partner should receive

- sandbox base URL
- credential or token issuance path
- webhook callback registration guidance
- test account or fixture guidance
- support contact for environment-level blockers

## Minimum setup checklist

1. Confirm the callback domains and IP allowlist requirements.
2. Validate authentication against a non-production environment.
3. Subscribe to the minimum event set needed for your flow.
4. Capture a first successful end-to-end transaction in sandbox.

## Common failure modes

- credentials created before the right tenant or account context exists
- callbacks blocked by unregistered domains
- webhook signatures not validated consistently across environments
- product-specific requirements documented outside the core portal
