---
description: "How the technical reference should be organized."
icon: book-open
---

# Reference overview

## Recommended hierarchy

1. Platform-wide concepts first
2. Product-family reference second
3. Endpoint detail generated from OpenAPI
4. Operational appendices for events, errors, and limits

## Why this matters

OEC appears to be unifying multiple API surfaces. A good reference model makes it easy to add product families later without rebuilding the portal each time.

## What belongs in authored pages

- auth and credential lifecycle
- environments and promotion path
- event model
- error taxonomy
- rate limits and reliability expectations

## What belongs in OpenAPI

- endpoints
- request and response schemas
- operation-specific examples
- tags and grouping
