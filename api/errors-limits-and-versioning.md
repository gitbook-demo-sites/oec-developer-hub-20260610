---
description: "Operational expectations around failure handling and change management."
icon: triangle-exclamation
---

# Errors, limits, and versioning

## Partners need answers to three questions

1. What failed?
2. Should I retry?
3. Will this behavior change without warning?

## Document explicitly

- error classes and example responses
- retryable versus terminal conditions
- rate limit behavior
- deprecation windows
- versioning or compatibility guarantees

{% hint style="info" %}
This is also where changelog and migration guidance should link in once the production portal adds a release-notes surface.
{% endhint %}
