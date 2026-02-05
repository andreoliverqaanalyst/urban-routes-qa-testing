# BUG-002 — Card number field incorrectly validates 11 characters and enables "Add" button

## Preconditions
- Google Chrome version 141.0.7390.123 (Official Build, 64-bit)
- Mozilla Firefox Browser version 144.0 (64-bit)
- User has access to the payment method screen

---

## Steps to Reproduce
1. Enter valid addresses in the **“From”** and **“To”** fields.
2. Click on **Payment Method**.
3. Click the **“+” (Add payment method)** icon.
4. In the **Card Number** field, enter **only 11 characters**.
5. Observe the validation behavior and the state of the **“Add”** button.

---

## Expected Result
- The **Card Number** field should reject card numbers with only **11 characters**.
- The **“Add”** button should remain **disabled**.

---

## Actual Result
- The **Card Number** field incorrectly accepts **11 characters**.
- The **“Add”** button becomes **enabled**, allowing the user to proceed.

---

## Severity
Medium

## Priority
High

---

## Environment
- Google Chrome version 141.0.7390.123 (Official Build, 64-bit)  
  Resolution: 1280×720
- Mozilla Firefox Browser version 144.0 (64-bit)  
  Resolution: 1920×1080

---

## Evidence
Screenshots and screen recordings related to this issue are attached in Jira.

