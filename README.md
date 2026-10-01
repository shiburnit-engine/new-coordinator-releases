# New Coordinator Releases

Public verified release channel for New Coordinator WordPress packages, signed metadata, checksums, and update delivery.

## Purpose

This repository contains release artifacts only. The New Coordinator source remains in the private `shiburnit-engine/new-coordinator` repository.

## Security boundary

- Do not store source-development secrets, API keys, signing private keys, WordPress credentials, or deployment credentials here.
- Release metadata must be cryptographically signed by the independent New Coordinator release process before WordPress trusts it.
- Published package identity and checksums are immutable for a released version.
- New Coordinator must fail closed when release metadata, signature, trusted package location, or checksum validation fails.
- This release channel must not depend on the old Coordinator, Coordinator Core, Development Bootstrap, Development Operator, or Handoff components.

## Publication state

Release channel initialized. Signed package publication is not yet enabled.
