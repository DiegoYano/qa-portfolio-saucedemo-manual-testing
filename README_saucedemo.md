# Manual QA Testing Portfolio — SauceDemo (Swag Labs)

Self-directed manual QA project covering the full cycle: test design, execution,
evidence capture, regression checklist and execution summary.

---

## Results

| Metric              | Value                    |
|---------------------|--------------------------|
| Test cases designed | 10                       |
| Test cases executed | 10                       |
| Passed              | 10                       |
| Failed              | 0                        |
| Defects logged      | 0                        |
| Account under test  | `standard_user`, `locked_out_user` |
| Browser             | Google Chrome            |
| Executed            | Jun/2026               |

All ten cases passed against the standard account. See
[What I'm testing next](#what-im-testing-next) for the follow-up round.

---

## Application under test

SauceDemo / Swag Labs — a demo e-commerce application published for testing practice.

---

## Scope

Functional and negative testing across the core purchase path:

- Valid login
- Invalid login and error message validation
- Locked-out user handling
- Product listing
- Add product to cart
- Remove product from cart
- Cart badge validation
- Product sorting by price
- Checkout required-field validation
- Complete checkout
- Logout
- Regression checklist for the above

**Test case selection.** Cases were ordered by user frequency rather than by
feature complexity — every user logs in, not every user reaches checkout. Login,
cart and logout therefore carry the most coverage.

---

## Detailed test results

| ID     | Feature                 | Status | Notes                                                        |
|--------|-------------------------|--------|--------------------------------------------------------------|
| TC-001 | Valid Login             | Pass   | User logged in and was redirected to the Products page        |
| TC-002 | Invalid Login           | Pass   | Error message displayed for invalid credentials               |
| TC-003 | Locked Out User Login   | Pass   | Locked-out user was prevented from logging in                 |
| TC-004 | Add Product to Cart     | Pass   | Product added to the cart successfully                        |
| TC-005 | Remove Product from Cart| Pass   | Product removed from the cart successfully                    |
| TC-006 | Cart Badge Validation   | Pass   | Badge updated correctly after adding and removing products    |
| TC-007 | Sort Products by Price  | Pass   | Products sorted correctly from low to high                    |
| TC-008 | Checkout Required Fields| Pass   | Required-field error message displayed                        |
| TC-009 | Complete Checkout       | Pass   | Checkout completed successfully                               |
| TC-010 | Logout                  | Pass   | User logged out and returned to the login page                |

Full cases with steps, preconditions and expected results are in
[`/test-cases`](./test-cases). Screenshot evidence is in
[`/screenshots`](./screenshots).

---

## What I'm testing next

Ten passes against the standard account tells me the happy path holds. It does not
tell me the tests are aggressive enough — a suite that never fails has not yet been
proven to be able to fail.

The next execution round targets that gap:

- Re-run the full suite against the alternate accounts available on the login page,
  which are seeded with deliberate defects
- Boundary and invalid input on checkout fields (empty, whitespace-only,
  overlong, special characters)
- Cart state persistence across logout and re-login
- Browser back-navigation mid-checkout
- Direct URL access to authenticated pages without a session

Findings will be logged in [`/bug-reports`](./bug-reports) using the report format
already defined there.

---

## Repository structure

```
test-cases/           Test case documents with steps and expected results
bug-reports/          Defect report format and logged defects
regression-checklist/ Regression checklist for the core purchase path
test-summary/         Test execution summary
screenshots/          Evidence captured during execution
```

---

## Test environment

| Item        | Detail                          |
|-------------|---------------------------------|
| Browser     | Google Chrome                   |
| OS          | [Windows 11 / macOS]            |
| Tools       | GitHub, GitHub Desktop, VS Code, Markdown |
| Test type   | Manual, functional and negative  |

---

## QA skills demonstrated

Manual testing · functional testing · negative testing · regression testing ·
test case design · defect report structure · expected vs. actual documentation ·
test execution summaries · technical documentation

---

## Author

**Diego Yano** — Burnaby, BC
QA Tester | Software Tester | Computer Science, Alexander College
[linkedin.com/in/diego-yano](https://linkedin.com/in/diego-yano)
