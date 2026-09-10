# Swag Labs – Cart Test Cases

## Test Scope

This document contains manual test cases for the Shopping Cart functionality of the Swag Labs website.

**Website:** https://www.saucedemo.com/

**Testing Type:** Manual Testing

---

## Test Cases

| Test Case ID | Test Scenario | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC-CART-001 | Verify Shopping Cart can be opened | Username: `standard_user` | User should be able to open the Shopping Cart. | The Shopping Cart page opened successfully. | Pass |
| TC-CART-002 | Verify added product appears in the cart | Product: Sauce Labs Backpack | The added product should appear in the Shopping Cart with its correct name. | Sauce Labs Backpack appeared in the Shopping Cart with the correct name. | Pass |
| TC-CART-003 | Verify product price is displayed in the cart | Product: Sauce Labs Backpack | The product price should be displayed correctly in the Shopping Cart. | The product price was displayed correctly in the Shopping Cart. | Pass |
| TC-CART-004 | Verify product quantity is displayed correctly | Product: Sauce Labs Backpack | The product quantity should be displayed correctly in the Shopping Cart. | The product quantity was displayed correctly as 1. | Pass |
| TC-CART-005 | Verify multiple products can be added to the cart | Products: Sauce Labs Backpack, Sauce Labs Bike Light | All selected products should be added and displayed in the Shopping Cart. | Both selected products were added and displayed in the Shopping Cart. | Pass |
| TC-CART-006 | Verify a product can be removed from the cart | Product: Sauce Labs Backpack | The selected product should be removed from the Shopping Cart. | Sauce Labs Backpack was removed successfully from the Shopping Cart. | Pass |
| TC-CART-007 | Verify Continue Shopping button works | Product: Sauce Labs Backpack | Clicking Continue Shopping should return the user to the Products page. | Clicking Continue Shopping returned the user to the Products page. | Pass |
| TC-CART-008 | Verify Checkout button is available | Product: Sauce Labs Backpack | The Checkout button should be visible and available in the Shopping Cart. | The Checkout button was visible and available in the Shopping Cart. | Pass |

---

## Test Summary

Eight Cart test cases were executed to verify the Shopping Cart functionality.

All eight executed test cases passed according to their expected results.

---

## Test Data

**Username:** `standard_user`

**Password:** `secret_sauce`