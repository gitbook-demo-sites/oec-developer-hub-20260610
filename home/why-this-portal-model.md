---
description: "Why OEC should unify partner and internal API documentation in one controlled surface."
icon: sitemap
---

# Why this portal model

OEC's likely risk is not missing pages. It is fragmented ownership across acquired products, inconsistent rollout quality, and a developer experience that breaks whenever internal context lives somewhere external teams cannot discover.

{% hint style="info" %}
This demo assumes OEC wants one canonical partner portal with authenticated enrichment for employees, TAMs, and support teams instead of a fully separate internal wiki for API operations.
{% endhint %}

## Why one portal is the better shape

- Partners get a stable entrypoint.
- Internal teams reuse the same structure and terminology.
- Product launches do not need a second content migration into an employee-only surface.
- Support can link customers to public docs while still keeping internal runbooks protected.

## What changes when login matters

The goal is not "gate everything." The goal is to make the right content public by default, then layer restricted content where it is actually sensitive.

Examples of public content:

- onboarding steps
- authentication basics
- API lifecycle and changelog
- webhook contracts
- testing and certification

Examples of authenticated or role-restricted content:

- customer-specific launch checklists
- internal escalation paths
- support macros and troubleshooting heuristics
- roadmap or deprecation timing not ready for broad release
- operational dashboards and ownership notes

## Recommended information architecture

1. `Home` for orientation and journey design
2. `Partner guides` for task-driven implementation
3. `API reference` for durable technical truth
4. `Access and support` for login, roles, and restricted overlays

## What to avoid

- Separate portals per acquired product before the core model is unified
- Hand-authored endpoint sprawl when OpenAPI can own the reference later
- Hiding access requirements until after a partner has already started integrating
