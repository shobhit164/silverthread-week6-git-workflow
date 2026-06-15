# Merge Conflict Documentation

## Conflict

Shobhit, Nikita, and Payal intentionally created one simple conflict while merging `bugfix/checkout-button-copy` into `main`.

Both `feature/promo-banner` and `bugfix/checkout-button-copy` changed the promotional banner line in `src/index.html`:

- `feature/promo-banner` changed it to a seasonal sale message.
- `bugfix/checkout-button-copy` changed it to a free-shipping message while also fixing checkout text.

Git could not automatically choose which banner text should remain because both branches edited the same line.

## Resolution

The team reviewed both changes and combined the intent into one final banner:

> Weekend sale: save 15% and get free shipping on orders over $75.

This preserved the promotional campaign from the feature branch and the shipping message from the bugfix branch.

For the product card section, Shobhit, Nikita, and Payal kept the improved `purchase-row` layout and also kept the clearer button text from the bugfix branch:

> Add tote to checkout

## Why This Matters

The conflict showed why frequent communication and pull request reviews matter. Git identified the overlapping edit, and the team made a deliberate decision instead of accidentally overwriting someone else's work.
