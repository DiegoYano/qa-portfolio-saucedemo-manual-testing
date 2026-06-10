# TC-008 – Checkout Required Fields

## Objective

Verify that the checkout form displays validation errors when required fields are left empty.

## Preconditions

- User is logged in.
- User has at least one product in the cart.
- User is on the Checkout Information page.

## Test Data

- Username: standard_user
- Password: secret_sauce
- Product: Sauce Labs Backpack

## Test Steps

1. Log in with valid credentials.
2. Add a product to the cart.
3. Open the cart.
4. Click Checkout.
5. Leave all required fields blank.
6. Click Continue.

## Expected Result

The system should display an error message indicating that required fields must be completed.

## Actual Result

The system displayed an error message for the missing required fields.

## Status

Pass

## Notes

The checkout form correctly prevented the user from continuing without required information.