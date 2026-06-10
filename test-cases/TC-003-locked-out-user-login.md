# TC-003 – Locked Out User Login

## Objective

Verify that a locked out user cannot log in to the application.

## Preconditions

- User is on the SauceDemo login page.
- User has locked out account credentials.

## Test Data

- Username: locked_out_user
- Password: secret_sauce

## Test Steps

1. Open the SauceDemo login page.
2. Enter the locked out username.
3. Enter the valid password.
4. Click the Login button.

## Expected Result

The user should not be logged in, and a locked out user error message should be displayed.

## Actual Result

The user was not logged in, and a locked out user error message was displayed.

## Status

Pass

## Notes

This is a negative test case. The error message is expected behaviour.