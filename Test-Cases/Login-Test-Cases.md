# Swag Labs – Login Test Cases

## Test Scope

This document contains manual test cases for the Login functionality of the Swag Labs website.

**Website:** https://www.saucedemo.com/

**Testing Type:** Manual Testing

---

## Test Cases

| Test Case ID | Test Scenario | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC-LOGIN-001 | Login with valid standard user | Username: `standard_user`<br>Password: `secret_sauce` | User should be successfully logged in and redirected to the Products page. | User was successfully logged in and redirected to the Products page. | Pass |
| TC-LOGIN-002 | Login with locked-out user | Username: `locked_out_user`<br>Password: `secret_sauce` | Login should fail and an appropriate error message should be displayed. | Login failed and the message "Epic sadface: Sorry, this user has been locked out." was displayed. | Pass |
| TC-LOGIN-003 | Login with problem user | Username: `problem_user`<br>Password: `secret_sauce` | User should be successfully logged in and redirected to the Products page. | User was successfully logged in. However, some product images were displayed incorrectly. | Pass |
| TC-LOGIN-004 | Login with performance glitch user | Username: `performance_glitch_user`<br>Password: `secret_sauce` | User should be successfully logged in and redirected to the Products page. | User was successfully logged in and redirected to the Products page. | Pass |
| TC-LOGIN-005 | Login with error user | Username: `error_user`<br>Password: `secret_sauce` | User should be successfully logged in and redirected to the Products page. | User was successfully logged in and redirected to the Products page. | Pass |
| TC-LOGIN-006 | Login with visual user | Username: `visual_user`<br>Password: `secret_sauce` | User should be successfully logged in and redirected to the Products page. | User was successfully logged in and redirected to the Products page. | Pass |
| TC-LOGIN-007 | Login with empty username | Username: Empty<br>Password: `secret_sauce` | A validation error should be displayed asking the user to enter a username. | Not executed yet. | Not Executed |
| TC-LOGIN-008 | Login with empty password | Username: `standard_user`<br>Password: Empty | A validation error should be displayed asking the user to enter a password. | Not executed yet. | Not Executed |
| TC-LOGIN-009 | Login with both fields empty | Username: Empty<br>Password: Empty | A validation error should be displayed and login should fail. | Not executed yet. | Not Executed |
| TC-LOGIN-010 | Login with invalid password | Username: `standard_user`<br>Password: `wrong_password` | Login should fail and an appropriate error message should be displayed. | Not executed yet. | Not Executed |
| TC-LOGIN-007 | Login with empty username | Username: Empty<br>Password: `secret_sauce` | A validation error should be displayed asking the user to enter a username. | Username is required. | Pass |
| TC-LOGIN-008 | Login with empty password | Username: `standard_user`<br>Password: Empty | A validation error should be displayed asking the user to enter a password. | Password is required. | Pass |
| TC-LOGIN-009 | Login with both fields empty | Username: Empty<br>Password: Empty | A validation error should be displayed and login should fail. | Username is required. | Pass |
| TC-LOGIN-010 | Login with invalid password | Username: `standard_user`<br>Password: `wrong_password` | Login should fail and an appropriate error message should be displayed. | "Epic sadface: Username and password do not match any user in this service" was displayed. | Pass |
---

## Test Summary

Six login test cases were executed using the usernames provided by the Swag Labs website.

All six executed test cases passed according to their expected results.

During testing, an issue was observed with the `problem_user`: some product images were displayed incorrectly after successful login.

This issue is related to the Products functionality and will be documented separately as a Bug Report.

---

## Test Data

### Accepted Usernames

- `standard_user`
- `locked_out_user`
- `problem_user`
- `performance_glitch_user`
- `error_user`
- `visual_user`

### Password

```text
secret_sauce