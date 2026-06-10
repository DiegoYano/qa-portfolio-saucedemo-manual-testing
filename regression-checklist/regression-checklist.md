# Regression Checklist – SauceDemo

## Project

Manual QA Testing Portfolio – SauceDemo

## Tester

Diego Yano

## Purpose

This checklist is used to verify that the main features of the SauceDemo application continue to work correctly after updates, changes, or fixes.

---

## Login

- [ ] Valid user can log in successfully.
- [ ] Invalid user cannot log in.
- [ ] Locked out user receives an appropriate error message.
- [ ] Error messages are clear and visible.
- [ ] User remains on the login page after failed login.
- [ ] Password field hides entered characters.

---

## Products Page

- [ ] Products are displayed correctly after login.
- [ ] Product names are visible.
- [ ] Product images are visible.
- [ ] Product prices are visible.
- [ ] Product descriptions are visible.
- [ ] Product sorting dropdown is available.
- [ ] Products can be sorted by name from A to Z.
- [ ] Products can be sorted by name from Z to A.
- [ ] Products can be sorted by price from low to high.
- [ ] Products can be sorted by price from high to low.

---

## Cart

- [ ] User can add one product to the cart.
- [ ] User can add multiple products to the cart.
- [ ] Cart badge updates correctly after adding products.
- [ ] User can open the cart page.
- [ ] Cart page displays selected products correctly.
- [ ] User can remove a product from the cart.
- [ ] Cart badge updates correctly after removing products.
- [ ] Cart is empty when all products are removed.

---

## Checkout

- [ ] User can start checkout from the cart page.
- [ ] Checkout form displays First Name, Last Name, and Postal Code fields.
- [ ] User cannot continue checkout with all required fields empty.
- [ ] User cannot continue checkout when First Name is missing.
- [ ] User cannot continue checkout when Last Name is missing.
- [ ] User cannot continue checkout when Postal Code is missing.
- [ ] User can continue checkout with valid information.
- [ ] Checkout Overview page displays selected products.
- [ ] Checkout Overview page displays item total, tax, and total.
- [ ] User can complete checkout successfully.
- [ ] Order confirmation message is displayed after completing checkout.

---

## Logout

- [ ] User can open the menu.
- [ ] User can log out successfully.
- [ ] User is redirected to the login page after logout.
- [ ] User cannot access the products page after logging out by using the browser back button.

---

## General UI

- [ ] Main buttons are visible and clickable.
- [ ] Page layout is consistent.
- [ ] Text is readable.
- [ ] No broken images are displayed.
- [ ] Navigation works as expected.