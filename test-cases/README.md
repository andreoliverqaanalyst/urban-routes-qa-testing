# Test Cases — Urban Routes

This document presents a selection of **manual test cases** created for the
Urban Routes application.  
The test cases were designed using **Equivalence Partitioning** and
**Boundary Value Analysis**, focusing on functional and validation scenarios.

Only a subset of representative test cases is included for portfolio purposes.

---

## TC-001 — Validate name field length (Boundary Value Analysis)

**Preconditions**
- Application is opened
- User is on the registration or input form screen

**Steps**
1. Enter a name with **2 characters** in the name field.
2. Enter a name with **14 characters** in the name field.
3. Attempt to submit the form.

**Expected Result**
- The system accepts names with a length between **2 and 14 characters**.
- No validation error message is displayed.

---

## TC-002 — Validate card number with insufficient length

**Preconditions**
- User is on the payment method screen

**Steps**
1. Click on **Add payment method**.
2. Enter a card number with **only 11 characters**.
3. Observe the state of the **Add** button.

**Expected Result**
- The system rejects card numbers with fewer than the required number of characters.
- The **Add** button remains disabled.

---

## TC-003 — Successful car reservation (Happy Path)

**Preconditions**
- Application is opened
- Valid pickup and destination addresses are available

**Steps**
1. Enter a valid address in the **From** field.
2. Enter a valid address in the **To** field.
3. Select a car type.
4. Confirm the reservation.

**Expected Result**
- The car is successfully reserved.
- A confirmation message is displayed to the user.

---

## Notes
- These test cases were selected to demonstrate different testing techniques:
  - Boundary Value Analysis
  - Validation testing
  - Happy path functional testing
- Additional test cases were created and maintained in spreadsheet format during the project.

## 📎 Additional Documentation

The complete set of test cases for this project was originally documented
in spreadsheet format during the testing phase.

The file **urban-routes-test-cases-portuguese-version.xlsx** is included in
this repository as a reference to the full testing scope and documentation
process.
