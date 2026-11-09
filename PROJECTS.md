# Project map

Socio Studios is an organization containing separate projects, not a repository
with repositories nested inside it. This profile repository holds public-facing
studio documentation only.

| Component | Proposed repository | Boundary | Availability |
| --- | --- | --- | --- |
| re:morse | remorse | Desktop application, session authority, speech pipeline and shared event contracts | Existing prototype; organization migration pending |
| Phone and watch | companion | One Android Gradle project with app and wear modules | Development; migration pending |
| Conversation playground | Within remorse initially | Licensed fixture acquisition, replay, scoring and evidence | Implemented locally; public packaging pending |
| Games | games | Conversation-related interactive experiments | Planned; scope to be established |
| Media | media | YouTube plans, scripts, demos and supporting explanations | Planned; no published videos announced |
| Studio website | socio-studios.github.io | Static public introduction and project links | Planned |

These are destination names, not links to repositories that necessarily exist.
We will link published projects here after their setup and verification.

## Shared boundaries

- The hub owns the canonical transcript and speaker identifiers.
- Clients render revisions rather than inventing competing speaker identities.
- Raw observations, recognition estimates and model interpretations stay distinct.
- Test recordings and model weights are acquired separately with attribution.
- Private conversations, credentials and local machine settings are not public assets.

Repository separation does not mean copying shared source into every project.
Versioned contracts and compatible releases will define integration points.
