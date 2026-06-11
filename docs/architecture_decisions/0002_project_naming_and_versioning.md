# ADR-002 — Project Naming and Versioning

## Context

The name Hephaestus references the Greek God of the forge. Hephaestus created all the weapons of the gods in Olympus and was worshipped in the manufacturing and industrial centres of Greece. I can think of no better name for a tool that enables software engineers and developers alike to forge automated processes within their applications and tools.

The versioning system will follow standard MAJOR.MINOR.PATCH format.

## Decision

The software will be called Hephaestus and will use the MAJOR.MINOR.PATCH versioning format. The organization is called hephaestusio due to hephaestus and hephaestus-dev already being taken. The proto namespace versioning will follow the format of adding the version number after the name. Ex:

- hephaestus.v1

## Consequences

Deployments will need to follow a strict versioning system to help maintain organization with releases.