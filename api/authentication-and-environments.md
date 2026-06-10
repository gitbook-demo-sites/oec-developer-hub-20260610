---
description: "The first technical concepts a partner needs before implementation."
icon: key
---

# Authentication and environments

## Document clearly

- how a partner gets credentials
- how sandbox and production differ
- where callback or redirect configuration happens
- whether auth scopes or claims change by product family

## Recommended structure

{% tabs %}
{% tab title="Sandbox" %}

Explain how to obtain non-production credentials, what data quality to expect, and how quickly environment changes propagate.

{% endtab %}
{% tab title="Production" %}

Explain who approves promotion, what security checks are required, and what support path exists for production credential or callback issues.

{% endtab %}
{% endtabs %}

{% hint style="warning" %}
If some auth guidance is partner-safe but some is internal-only, keep the public baseline on this page and layer the sensitive operational notes through authenticated content in the access space.
{% endhint %}
