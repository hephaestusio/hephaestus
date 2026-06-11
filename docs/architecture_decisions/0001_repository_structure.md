# ADR-001 — Repository Structure

## Context

The structure of the repositories would influence maintainability down the line as well as uphold a professional standard that will easily onboard future developers. Research was done on Temporal's codebases to get an idea of what repository structures created a solid foundation for this type of project.

## Decision

The project will be structured using multiple separate repositories. At the time of creation, there will be 4 separate repositories:

- hephaestus
- hephaestus-api
- hephaestus-sdk-go
- hephaestus-sdk-python

## Consequences

While decoupling will allow for autonomy, keeping each repository updated and in sync with one another will be a challenge. For example, all proto changes will flow through the hephaestus-api repository creating an organized point of truth. However, anytime a change is made to one SDK's repository, the same change must also be implemented in the other SDK repositories.