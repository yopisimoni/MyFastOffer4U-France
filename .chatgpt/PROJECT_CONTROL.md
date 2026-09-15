# Project Control — MyFastOffer4U France

## Canonical identity
- Project: MyFastOffer4U France
- Repository: yopisimoni/MyFastOffer4U-France
- Default branch: main
- Production URL: https://fr.myfastoffer4u.com
- Market: France
- Purpose: France-focused consumer guidance and recurring-cost analysis/comparison product.

## Scope boundaries
- This repository is separate from the UK MyFastOffer4U project.
- Do NOT reuse UK copy, analytics IDs, forms, partner flows, redirects, or deployment assumptions unless explicitly requested.
- Do NOT mix this repository with next.myfastoffer4u.com or MarocVows.

## Deployment / infrastructure
- The live URL is documented in the repository README.
- Verify the actual deployment mechanism before changing deployment configuration.
- A GitHub commit is not proof that the production subdomain changed.

## Protected project facts
- Preserve France localization and France-specific product logic.
- Preserve analytics scoping unless explicitly changing analytics.
- Do not import identifiers from any other project.

## Working protocol
1. Read this file.
2. Inspect current repository files.
3. Verify the relevant live page when production behavior is involved.
4. Make the smallest safe change.
5. Commit.
6. Verify live behavior when applicable.
7. Report any remaining uncertainty.

## Definition of done
- correct repository used;
- requested change committed;
- production/deployment checked when applicable;
- France-specific behavior preserved;
- no cross-project identifiers introduced;
- no obvious regression.
