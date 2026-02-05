# Urban Routes – Bug Report

## BUG-001 – Cancel button not clickable on "Car Reserved" pop-up

**Preconditions:**
- Google Chrome browser version 141.0.7390.123 (Official Build) (64-bit) is opened
- Mozilla Firefox browser version 144.0 (64-bit) is opened
- All mandatory fields are filled in
- Car is successfully reserved
- "Car Reserved" pop-up window is displayed
- Free waiting timer is active

**Steps to reproduce:**
1. Click on the **Cancel (X)** button on the "Car Reserved" pop-up.
2. Verify whether the button is clickable and if the confirmation message  
   *"Are you sure you want to cancel the trip?"* appears.

**Expected result:**
The "Trip canceled" window is displayed, the reservation is canceled without any charge, and the user is redirected to the home screen.

**Actual result:**
The **Cancel** button on the "Car Reserved" pop-up is not clickable, preventing the user from canceling the request.

**Environment:**
- Google Chrome 141.0.7390.123 (Official Build) (64-bit), Resolution: 1280x720
- Mozilla Firefox 144.0 (64-bit), Resolution: 1920x1080

**Severity:** High  
**Priority:** High
