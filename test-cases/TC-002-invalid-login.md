# TC-002 – Invalid Login

## Objective

Verify that the system displays an error message when the user enters invalid login credentials.

## Preconditions

- User is on the SauceDemo login page.

## Test Data

- Username: standard_user
- Password: wrong_password

## Test Steps

1. Open the SauceDemo login page.
2. Enter a valid username.
3. Enter an invalid password.
4. Click the Login button.

## Expected Result

The user should not be logged in, and an error message should be displayed.

## Actual Result

The user was not logged in, and an error message was displayed.

## Status

Pass

## Notes

The system correctly prevented login with invalid credentials.