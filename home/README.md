---
description: "Landing space for OEC's partner and developer portal."
icon: house
cover: https://oeconnection.com/wp-content/uploads/2025/12/Homepage-Hero-8-1024x573.jpg
coverY: 0
layout:
  width: wide
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: false
  outline:
    visible: false
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
---

# OEC Developer Hub

{% columns %}
{% column width="55%" %}
Everything is easier when the partner journey, API contract, and internal rollout context live in one connected portal. External developers should be able to discover, test, and launch quickly, while OEC teams can add authenticated guidance without fragmenting the docs surface.

<a class="button primary" href="https://oeconnection.com/login/">Log in to OEC</a>
<a class="button secondary" href="https://oeconnection.com/support/">Get support</a>

<button type="button" class="button primary" data-action="ask" data-icon="gitbook-assistant">Search the OEC docs</button>

<button type="button" class="button secondary" data-action="ask" data-query="How do I start a new partner integration?" data-icon="plug">New integration</button> <button type="button" class="button secondary" data-action="ask" data-query="How do authentication and environments work?" data-icon="key">Authentication</button> <button type="button" class="button secondary" data-action="ask" data-query="Where do I find API reference and webhook events?" data-icon="code">API reference</button>
{% endcolumn %}

{% column width="45%" %}
{% hint style="success" icon="circle-info" %}
**Portal model**

This homepage is intentionally a landing page first, not a docs index. The goal is to let partners search, choose a path, and get into the right workflow quickly, while preserving room for authenticated OEC-only overlays deeper in the portal.
{% endhint %}
{% endcolumn %}
{% endcolumns %}

***

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
      <td><a href="https://app.gitbook.com/s/Zf16hXU4sTBoarXMu0IT/README">README</a></td>
    </tr>
    <tr>
      <td><i class="fa-code" style="color:#0B6E69;"></i></td>
      <td><strong>API reference</strong></td>
      <td>Authentication, core resources, event patterns, errors, and versioning approach.</td>
      <td><a href="https://app.gitbook.com/s/ov7xDc9uLg04p7VFGo2m/README">README</a></td>
    </tr>
    <tr>
      <td><i class="fa-user-lock" style="color:#0B6E69;"></i></td>
      <td><strong>Access and support</strong></td>
      <td>Login model, role-based visibility, internal overlays, and support escalation.</td>
      <td><a href="https://app.gitbook.com/s/3qp3KhmnSXFshs3kOezs/README">README</a></td>
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
2. Start the [partner onboarding flow](https://app.gitbook.com/s/Zf16hXU4sTBoarXMu0IT/getting-started/partner-onboarding).
3. Review [authentication and environments](https://app.gitbook.com/s/ov7xDc9uLg04p7VFGo2m/authentication-and-environments).
4. Confirm [login, roles, and restricted content behavior](https://app.gitbook.com/s/3qp3KhmnSXFshs3kOezs/login-and-role-model).

## Internal rollout notes

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
      <td><i class="fa-sitemap" style="color:#0B6E69;"></i></td>
      <td><strong>Why this portal model</strong></td>
      <td>Why OEC should unify partner and internal API documentation in one controlled surface.</td>
      <td><a href="why-this-portal-model.md">why-this-portal-model.md</a></td>
    </tr>
    <tr>
      <td><i class="fa-route" style="color:#0B6E69;"></i></td>
      <td><strong>Developer journey</strong></td>
      <td>The intended end-to-end flow for a partner developer using the OEC portal.</td>
      <td><a href="developer-journey.md">developer-journey.md</a></td>
    </tr>
    <tr>
      <td><i class="fa-people-arrows" style="color:#0B6E69;"></i></td>
      <td><strong>Portal operating model</strong></td>
      <td>How the portal should be owned and evolved inside OEC.</td>
      <td><a href="portal-operating-model.md">portal-operating-model.md</a></td>
    </tr>
    <tr>
      <td><i class="fa-rocket" style="color:#0B6E69;"></i></td>
      <td><strong>Launch plan</strong></td>
      <td>A pragmatic launch sequence for the first OEC API portal release.</td>
      <td><a href="launch-plan.md">launch-plan.md</a></td>
    </tr>
  </tbody>
</table>
