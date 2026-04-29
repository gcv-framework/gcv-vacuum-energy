# GitHub Upload Instructions

This repository is a hub/index. Do not upload duplicate PDF/source/archive packages to GitHub when the canonical package is already on Zenodo/OSF.

## What to upload or replace

Replace the hub/index files only:

```text
README.md
ROUTE_MAP.md
CITATION.md
CITATION.cff
PROVENANCE.md
CLAIMS_MAP.md
PRIORITY_MAP.md
SEARCH_INDEXING.md
CHANGELOG.md
OSF_WIKI.md
docs/00_start_here.md
docs/12_gate_architecture.md
tables/doi_index.md
tables/module_dependency_table.md
```

Do not upload:

```text
gcv_governance_route_gate_architecture_v1.0.0.pdf
gcv_governance_route_gate_architecture_v1.0.0.tex
gcv_governance_route_gate_architecture_v1.0.0.zip
SHA256SUMS.txt
MANIFEST.txt
```

Those files belong in Zenodo and OSF.

## Commit message

Suggested commit message:

```text
Add Governance Route DOI to route-map hub
```

## Recommended GitHub repository topics

```text
gcv-framework
cosmological-constant
vacuum-energy
general-relativity
flux-compactification
source-assignment
governance-bridge
gate-architecture
branch-viability
dark-energy
cosmology
```

## GitHub release

Do not create a new GitHub release until the OSF mirror and OSF registration links for the Governance Route / Gate Architecture record are available.

When ready, create one clean hub release:

```text
Tag: gcv-route-map-v1.0.1
Title: GCV Route Map and Provenance Index v1.0.1
```

Suggested release notes:

```text
Adds the live Governance Route / Gate Architecture record and provenance links to the GCV route-map hub.

- Governance Route concept DOI: 10.5281/zenodo.19874410
- Governance Route version DOI v1.0.0: 10.5281/zenodo.19874411
- Adds OSF mirror and registration links for the route record.
- Updates route/gate architecture entries, citation guidance, DOI index, provenance map, and dependency route.

This GitHub repository remains a navigation, citation, and provenance hub. The authoritative scientific files remain on Zenodo and OSF mirrors/registrations.
```

## After OSF is complete

After the OSF mirror/registration is live, update:

```text
docs/12_gate_architecture.md
PROVENANCE.md
tables/doi_index.md
OSF_WIKI.md
README.md
CHANGELOG.md
```

Replace TODO fields with the OSF project and registration URLs.

## Link targets

Use:

```text
Concept DOI: https://doi.org/10.5281/zenodo.19874410
Version DOI: https://doi.org/10.5281/zenodo.19874411
```

Use the concept DOI for homepage, YouTube descriptions, GitHub README, and general navigation. Use the version DOI when citing the exact v1.0.0 paper.
