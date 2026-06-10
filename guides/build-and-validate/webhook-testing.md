---
description: "How to validate event delivery and callback behavior."
icon: satellite-dish
---

# Webhook testing

## Validate these first

- signature verification
- retry behavior
- idempotent processing
- ordering assumptions
- dead-letter or replay handling

{% tabs %}
{% tab title="Developer view" %}

Capture raw payloads and headers from the first successful test deliveries. Keep examples close to the docs so new teams can compare live traffic with expected shapes.

{% endtab %}
{% tab title="Internal OEC view" %}

Authenticated overlays can include event routing caveats, internal event ownership, and escalation guidance for known provider-side issues.

{% endtab %}
{% endtabs %}
