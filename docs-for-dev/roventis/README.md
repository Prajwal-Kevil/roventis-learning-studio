# Roventis product profile

Roventis Learning Studio is the Roventis Technologies presentation and deployment profile for DeepTutor. It is intended for teams building websites, mobile applications, SaaS products, and desktop software.

## Product principles

1. Keep customer data and credentials inside the configured workspace and provider boundaries.
2. Make generated research, learning paths, and deliverables inspectable and exportable.
3. Prefer small, reversible customizations over invasive changes to upstream runtime contracts.
4. Preserve upstream attribution and document every Roventis-specific behavior.

## Suggested customer workspace layout

Use separate workspaces for **Product**, **Engineering**, **Customer Success**, and **Operations**. Keep customer-specific material isolated from the shared product profile, and connect only the sources needed for each workspace.

## Extension rule

New Roventis features should include a focused test, a short user-facing description, and an entry in `ROVENTIS_CUSTOMIZATION.md` or this guide. Do not put API keys, customer documents, or deployment secrets in the repository.
