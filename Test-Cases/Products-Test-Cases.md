# Swag Labs – Products Test Cases

## Test Scope

This document contains manual test cases for the Products functionality of the Swag Labs website.

**Website:** https://www.saucedemo.com/

**Testing Type:** Manual Testing

---

## Test Cases

| Test Case ID | Test Scenario                                 | Test Data                                             | Expected Result                                                        | Actual Result                                                     | Status        |
|--------------|-----------------------------------------------|-------------------------------------------------------|------------------------------------------------------------------------|-------------------------------------------------------------------|---------------|
| TC-PROD-001  | Verify Products page is displayed after login | Username: `standard_user`<br>Password: `secret_sauce` | User should be redirected to the Products page after successful login. | User was successfully redirected to the Products page.            | Pass          |
| TC-PROD-002  | Verify products are displayed                 | Username: `standard_user`                             | Products were displayed with product names, images, and prices.        | Products were displayed correctly with names, images, and prices. | Pass          |
| TC-PROD-003  | Verify product names are displayed            | Username: `standard_user`                             | Each product should have a visible product name.                       | All products had visible product names.                           | Pass          |
| TC-PROD-004  | Verify product prices are displayed           | Username: `standard_user`                             | Each product should have a visible and correctly formatted price.      | All products had visible prices with correct formatting.          | Pass          |
| TC-PROD-005  | Verify product images are displayed correctly | Username: `standard_user`                             | Each product should display its correct corresponding image.           | All products displayed their correct corresponding images.        | Pass          |
| TC-PROD-006  | Verify product details can be opened          | Username: `standard_user`                             | Clicking a product should open its product details page.               | The product details page opened successfully.                     | Pass          |
| TC-PROD-007  | Verify Add to Cart button is available        | Username: `standard_user`                             | Each available product should have an Add to Cart button.              | Each product had an Add to Cart button.                           | Pass          |
| TC-PROD-008 | Verify product sorting functionality | Username: `standard_user` | Products should be sorted according to the selected sorting option. | Products were sorted correctly according to the selected sorting option. | Pass |
