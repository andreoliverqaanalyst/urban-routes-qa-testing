# 🐞 BUG-003 — Available cars are not displayed on the map when address fields are cleared

## Preconditions
- Google Chrome version 141.0.7390.123 (Official Build, 64-bit) is opened
- Mozilla Firefox browser version 144.0 (64-bit) is opened
- Enter **"1917 Bay St"** in the **“From”** field
- Enter **"615 S Broadway"** in the **“To”** field
- Select **Personal** mode
- Select **Car Sharing** as the transportation type

---

## Steps to Reproduce
1. Clear the address from the **“From”** field.
2. Clear the address from the **“To”** field.
3. Observe whether available cars are displayed directly on the map.

---

## Expected Result
- The reservation screen allows clearing the address fields, as they are **not required** to book a shared car.
- Available cars are displayed on the map.
- The user can select a car directly from the map.

---

## Actual Result
- The map does **not display any vehicle icons**.
- Only route points **A** and **B** are shown.
- The user is unable to select a shared car from the map.

---

## Severity
Medium

## Priority
Medium

---

## Environment
- Google Chrome version 141.0.7390.123 (Official Build, 64-bit)
- Mozilla Firefox browser version 144.0 (64-bit)

---

## Evidence
Screenshots and screen recordings related to this issue are attached in Jira.

