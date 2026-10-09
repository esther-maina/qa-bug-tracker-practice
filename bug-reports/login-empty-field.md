# Bug Report: Login form accepts an empty email field

**Title:** Login form submits with an empty email field  
**Severity:** High  
**Priority:** High

## Environment

- App: LendFast Kenya Mobile App
- Version: 1.0.0
- Device: Samsung Galaxy A32
- OS: Android 11

## Preconditions

- The app is installed.
- The user is not logged in.

## Steps to Reproduce

1. Open the LendFast Kenya app.
2. Leave the email field empty.
3. Enter any password.
4. Tap the Login button.

## Expected Result

The app should display a validation error: "Email is required."

## Actual Result

The form submits without displaying any validation error.

## Impact

This creates an unauthorized access risk because users can bypass email validation entirely.
