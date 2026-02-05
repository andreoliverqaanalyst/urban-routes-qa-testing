# BUG-001 — Cancel button not clickable on "Car Reserved" pop-up

## Preconditions
- Google Chrome browser version 141.0.7390.123 (Official Build, 64-bit) is opened
- Mozilla Firefox browser version 144.0 (64-bit) is opened
- All mandatory fields are filled in
- Car is successfully reserved
- The **"Car Reserved"** pop-up window is displayed
- Free waiting timer is active

---

## Steps to Reproduce
1. Click on the **Cancel (X)** button on the **"Car Reserved"** pop-up.
2. Verify whether the button is clickable and if the confirmation message  
   **"Are you sure you want to cancel the trip?"** appears.

---

## Expected Result
- The **"Trip canceled"** window is displayed.
- The reservation is canceled **without any charge**.
- The user is redirected to the **home screen**.

---

## Actual Result
- The **Cancel (X)** button on the **"Car Reserved"** pop-up is **not clickable**.
- The user is **unable to cancel** the reservation.

---

## Severity
High

## Priority
High

---

## Environment
- Google Chrome version 141.0.7390.123 (Official Build, 64-bit)  
  Resolution: 1280×720
- Mozilla Firefox version 144.0 (64-bit)  
  Resolution: 1920×1080

---

## Evidence
Screenshots and screen recordings related to this issue are attached in Jira.
