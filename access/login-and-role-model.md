---
description: "A simple access model for one portal serving both partners and OEC employees."
icon: right-to-bracket
---

# Login and role model

## Recommended model

- anonymous visitors can browse high-level portal guidance
- authenticated partners see implementation and customer-safe technical detail
- authenticated OEC employees see internal overlays on top of the same core docs

## Why this beats a split portal

- fewer duplicated pages
- one search experience
- one canonical URL structure
- support can share public pages without losing access to internal context

## Example of adaptive content

{% if visitor.claims.role == "employee" %}
Internal-only rollout notes, escalation shortcuts, and support diagnostics can be shown here for OEC employees.
{% endif %}

{% hint style="success" %}
For a demo, the key is showing that login is a first-class entrypoint and that role-based content can live in one coherent experience.
{% endhint %}
