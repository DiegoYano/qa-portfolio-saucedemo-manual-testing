# TC-006 – Cart Badge Validation

## Objective

Verify that the cart badge updates correctly when products are added or removed.

## Preconditions

- User is logged in.
- User is on the Products page.

## Test Data

- Username: standard_user
- Password: secret_sauce
- Product 1: Sauce Labs Backpack
- Product 2: Sauce Labs Bike Light

## Test Steps

1. Log in with valid credentials.
2. Add the Sauce Labs Backpack to the cart.
3. Verify that the cart badge displays "1".
4. Add the Sauce Labs Bike Light to the cart.
5. Verify that the cart badge displays "2".
6. Remove one product.
7. Verify that the cart badge updates to "1".

## Expected Result

The cart badge should correctly display the number of products currently in the cart.

## Actual Result

The cart badge updated correctly after products were added and removed.

## Status

Pass

## Notes

The cart badge count matched the number of selected products.