---
description: "Landing space for OEC's partner and developer portal."
icon: house
---

# OEC Developer Hub

External partners should be able to discover, test, and launch quickly. Internal OEC teams should be able to layer in restricted rollout notes, support paths, and account-specific implementation context without fragmenting the docs surface.

<table data-view="cards">
  <thead>
    <tr>
      <th width="48"></th>
      <th></th>
      <th></th>
      <th data-hidden data-card-target data-type="content-ref"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><i class="fa-route" style="color:#0B6E69;"></i></td>
      <td><strong>Partner guides</strong></td>
      <td>Onboarding, environment setup, certification flow, and launch guidance.</td>
      <td><a href="https://app.gitbook.com/s/FbNda6lbrLue6QWOtkr6/README">README</a></td>
    </tr>
    <tr>
      <td><i class="fa-code" style="color:#0B6E69;"></i></td>
      <td><strong>API reference</strong></td>
      <td>Authentication, core resources, event patterns, errors, and versioning approach.</td>
      <td><a href="https://app.gitbook.com/s/f1W2PfBZBd1K2O1uYgH8/README">README</a></td>
    </tr>
    <tr>
      <td><i class="fa-user-lock" style="color:#0B6E69;"></i></td>
      <td><strong>Access and support</strong></td>
      <td>Login model, role-based visibility, internal overlays, and support escalation.</td>
      <td><a href="https://app.gitbook.com/s/ka3sGU9YEvIddqpo87yc/README">README</a></td>
    </tr>
  </tbody>
</table>

{% hint style="success" %}
This draft is optimized for the use case described in the OEC discovery notes: one portal that serves external developers well, while still allowing authenticated OEC employees to see additional operational context.
{% endhint %}

## What this demo is trying to prove

{% columns %}
{% column %}
### For external partners

- Find the right API surface quickly
- Understand access requirements before implementation
- Move from sandbox to production with fewer handoffs
- Self-serve answers around auth, errors, testing, and support
{% endcolumn %}

{% column %}
### For internal OEC teams

- Keep one canonical docs surface instead of product-by-product fragments
- Gate internal-only content behind login and claims
- Add implementation overlays without cloning public docs
- Give support and product teams a shared operational source
{% endcolumn %}
{% endcolumns %}

## Suggested first path

1. Read the [portal model](why-this-portal-model.md).
2. Start the [partner onboarding flow](https://app.gitbook.com/s/FbNda6lbrLue6QWOtkr6/getting-started/partner-onboarding).
3. Review [authentication and environments](https://app.gitbook.com/s/f1W2PfBZBd1K2O1uYgH8/authentication-and-environments).
4. Confirm [login, roles, and restricted content behavior](https://app.gitbook.com/s/ka3sGU9YEvIddqpo87yc/login-and-role-model).

## What is intentionally demonstrated here

- A strong top-level shell for an `OEC IO API` style portal
- A visible login path in the site chrome
- Public-to-private progression instead of separate disconnected tools
- A docs model that can later swap overview pages for OpenAPI-backed endpoint reference

## Quick links

- [Why this portal model](why-this-portal-model.md)
- [Developer journey](developer-journey.md)
- [Launch plan](launch-plan.md)
