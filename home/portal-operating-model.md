---
description: "How the portal should be owned and evolved inside OEC."
icon: people-arrows
---

# Portal operating model

This portal works only if OEC treats it as a shared product surface, not a one-time launch asset.

## Suggested ownership split

| Area | Primary owner | Supporting teams |
| --- | --- | --- |
| Navigation and IA | Platform product | Developer experience, support |
| API reference source | Engineering | Product, architecture |
| Onboarding guides | Developer experience | Solutions, TAMs |
| Restricted overlays | Support operations | Product, services |
| Release notes | Product marketing or PM | Engineering |

## Publishing model

- Public docs should cover the default partner path.
- Authenticated overlays should answer the internal questions support and field teams ask repeatedly.
- OpenAPI should become the source of truth for endpoint detail once specs are ready.
- Cross-space links should keep guides and reference tightly connected.

## Review rhythm

1. Weekly review of pages changed for launch-critical APIs
2. Monthly audit of support-driven additions
3. Quarterly cleanup of stale restricted overlays

{% hint style="warning" %}
If restricted content grows faster than public content, the portal will slowly turn back into an internal wiki with a public facade. That is the failure mode to watch.
{% endhint %}
