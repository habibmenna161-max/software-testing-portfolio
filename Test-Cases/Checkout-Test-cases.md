# Swag Labs – Checkout Test Cases

## Test Scope

This document contains manual test cases for the Checkout functionality of the Swag Labs website.

**Website:** https://www.saucedemo.com/

**Testing Type:** Manual Testing

---

## Test Cases

| Test Case ID | Test Scenario | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC-CHECKOUT-001 | Verify Checkout page can be opened | Product: Sauce Labs Backpack | The Checkout: Your Information page should be displayed. | The Checkout: Your Information page opened successfully with the required information fields. | Pass |
| TC-CHECKOUT-002 | Verify checkout information fields are displayed | Username: `standard_user` | First Name, Last Name, and ZIP/Postal Code fields should be displayed and available. | First Name, Last Name, and ZIP/Postal Code fields were displayed and available. | Pass |
| TC-CHECKOUT-003 | Verify checkout with valid information | First Name: `Menna`<br>Last Name: `Habib`<br>ZIP: `12345` | User should be able to continue to the Checkout: Overview page. | User successfully continued to the Checkout: Overview page. | Pass |
| TC-CHECKOUT-004 | Verify checkout with empty First Name | First Name: Empty<br>Last Name: `Habib`<br>ZIP: `12345` | An error message should be displayed indicating that First Name is required. | An error message indicating that First Name is required was displayed. | Pass |
| TC-CHECKOUT-005 | Verify checkout with empty Last Name | First Name: `Menna`<br>Last Name: Empty<br>ZIP: `12345` | An error message should be displayed indicating that Last Name is required. | An error message indicating that Last Name is required was displayed. | Pass |
| TC-CHECKOUT-006 | Verify checkout with empty ZIP/Postal Code | First Name: `Menna`<br>Last Name: `Habib`<br>ZIP: Empty | An error message should be displayed indicating that ZIP/Postal Code is required. | An error message indicating that ZIP/Postal Code is required was displayed. | Pass |
| TC-CHECKOUT-007 | Verify order overview information | Product: Sauce Labs Backpack | Product, price, item total, tax, and total should be displayed correctly. | Product, price, item total, tax, and total were displayed correctly. | Pass |
| TC-CHECKOUT-008 | Verify order can be completed | Product: Sauce Labs Backpack | Clicking Finish should complete the order and display an order confirmation message. | The order was completed successfully and the order confirmation page was displayed. | Pass |

---

## Test Summary

Eight Checkout test cases were executed to verify the Checkout functionality.

All eight executed test cases passed according to their expected results.

---

## Test Data

**Username:** `standard_user`

**Password:** `secret_sauce`

**First Name:** `Menna`

**Last Name:** `Habib`

**ZIP/Postal Code:** `12345`