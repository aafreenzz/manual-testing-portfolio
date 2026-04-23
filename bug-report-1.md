# Bug Report 1 — Checkout accepts spaces as valid input

**Severity:** Medium  
**App:** saucedemo.com  
**User:** problem_user  

## Steps to Reproduce
1. Log in with problem_user / secret_sauce
2. Add any item to cart
3. Click cart → Checkout
4. Enter only spaces in First Name, Last Name, and Zip Code
5. Click Continue

## Expected Result
App should show a validation error — spaces should not be accepted

## Actual Result
App proceeds to the next screen as if the input is valid

## Status
Open
