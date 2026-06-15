# Silverthread Week 6 Git Collaboration Workflow

Program: Full Stack Software Development  
Project Code: CPL-5559-FSDS  
Case Study: Week 6 WIL Project

## Scenario

Silverthread is helping a growing e-commerce client improve how its developers collaborate. This repository simulates a lightweight Git workflow where team members work in parallel, open pull requests, review changes, resolve one merge conflict, and merge everything back into `main`.

## Branching Model

- `main`: stable shared branch containing reviewed and integrated work.
- `feature/product-card-layout`: feature branch for the product card UI.
- `feature/promo-banner`: feature branch for promotional storefront content.
- `bugfix/checkout-button-copy`: bugfix branch for checkout button text and accessibility.

## Simulated Team Tasks

| Team Member | Branch | Task |
| --- | --- | --- |
| Aisha | `feature/product-card-layout` | Improve product card layout, price display, and inventory badge. |
| Mateo | `feature/promo-banner` | Add a seasonal promo banner to the storefront. |
| Priya | `bugfix/checkout-button-copy` | Fix unclear checkout button text and improve the call to action. |

## Deliverables Included

- Storefront mock files in `src/`
- Pull request review notes in `docs/pull-request-reviews.md`
- Merge conflict documentation in `docs/conflict-resolution.md`
- Git workflow summary in `docs/workflow-summary.md`
- Summary poster in `poster/git-workflow-poster.html`

## How to Review the Git Workflow

Run:

```bash
git log --oneline --graph --all
git branch --all
```

These commands show the separate feature and bugfix branches, merge commits, and final integrated `main` branch.
