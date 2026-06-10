---
description: "Reusable implementation patterns for OEC API integrations."
icon: puzzle-piece
---

# Common integration patterns

## Typical shape

1. Authenticate the caller
2. Submit or request the primary business object
3. Poll or subscribe for lifecycle updates
4. Reconcile asynchronous outcomes with downstream systems

## Where partners usually need help

- mapping OEC identifiers to partner-side systems
- understanding when to poll versus wait for events
- handling partial success or delayed completion states
- reconciling operational and business-level errors

## Best practice

Write guides around partner goals and link down into [reference pages](https://app.gitbook.com/s/XSPACE_API/README) for contract detail. Do not force developers to learn the product model only from endpoint listings.
