# Test Execution Summary – SauceDemo

## Project

Manual QA Testing Portfolio – SauceDemo

## Application Under Test

SauceDemo / Swag Labs

## Tester

Diego Yano

## Test Date

June 10, 2026

## Test Environment

- Browser: Google Chrome
- Operating System: Windows 11
- Device: Desktop / Laptop
- Test Type: Manual Functional Testing

---

## Objective

The objective of this test execution was to validate the main functionality of the SauceDemo application, including login, product listing, cart behavior, checkout flow, required field validation, sorting, and logout.

---

## Scope of Testing

The following areas were tested:

- Login functionality
- Invalid login validation
- Locked out user validation
- Product selection
- Add to cart
- Remove from cart
- Cart badge validation
- Product sorting
- Checkout required fields
- Complete checkout flow
- Logout functionality

---

## Test Results Summary

| Total Test Cases | Passed | Failed | Blocked | Not Run |
|---|---:|---:|---:|---:|
| 10 | 10 | 0 | 0 | 0 |

---

## Test Execution Notes

All test cases were executed manually using Google Chrome. Selected screenshots were added as evidence for successful login, cart validation, and checkout completion. No critical defects were found during this test cycle.

---

## Detailed Test Results

| Test Case ID | Feature | Status | Notes |
|---|---|---|---|
| TC-001 | Valid Login | Pass | User logged in successfully and was redirected to the Products page. |
| TC-002 | Invalid Login | Pass | Error message was displayed for invalid credentials. |
| TC-003 | Locked Out User Login | Pass | Locked out user was prevented from logging in. |
| TC-004 | Add Product to Cart | Pass | Product was added to the cart successfully. |
| TC-005 | Remove Product from Cart | Pass | Product was removed from the cart successfully. |
| TC-006 | Cart Badge Validation | Pass | Cart badge updated correctly after adding and removing products. |
| TC-007 | Sort Products by Price | Pass | Products were sorted correctly from low to high. |
| TC-008 | Checkout Required Fields | Pass | Required field error message was displayed. |
| TC-009 | Complete Checkout | Pass | Checkout was completed successfully. |
| TC-010 | Logout | Pass | User logged out successfully and returned to the login page. |

---

## Defects Found

No critical defects were identified during this test execution.

A sample defect report was created separately to demonstrate defect documentation structure.

---

## Overall Result

Passed

---

## Conclusion

The main features tested in the SauceDemo application worked as expected. The application allowed valid users to log in, add and remove products from the cart, validate checkout fields, complete the checkout process, and log out successfully.

This test execution demonstrates manual QA skills including test case execution, functional testing, negative testing, regression awareness, bug reporting structure, and clear documentation of expected versus actual results.