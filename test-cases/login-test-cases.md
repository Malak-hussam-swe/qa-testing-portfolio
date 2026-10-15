# Login Functionality - Test Cases

## Objective

To verify that the login functionality works correctly under different conditions.

## Test Case 1: Login with valid credentials

* **Test Case ID:** TC_LOGIN_001
* **Priority:** High
* **Preconditions:** A registered user account exists.
* **Test Steps:**

  1. Open the login page.
  2. Enter a valid email address.
  3. Enter the correct password.
  4. Click the Login button.
* **Expected Result:** The user should log in successfully and be redirected to the appropriate page.
* **Actual Result:** Not tested yet.
* **Status:** Not Run

## Test Case 2: Login with an incorrect password

* **Test Case ID:** TC_LOGIN_002
* **Priority:** High
* **Preconditions:** A registered user account exists.
* **Test Steps:**

  1. Open the login page.
  2. Enter a valid email address.
  3. Enter an incorrect password.
  4. Click the Login button.
* **Expected Result:** The user should see an appropriate error message and should not log in.
* **Actual Result:** Not tested yet.
* **Status:** Not Run

## Test Case 3: Login with empty fields

* **Test Case ID:** TC_LOGIN_003
* **Priority:** Medium
* **Preconditions:** The login page is open.
* **Test Steps:**

  1. Leave the email and password fields empty.
  2. Click the Login button.
* **Expected Result:** The application should request the required fields and should not log in the user.
* **Actual Result:** Not tested yet.
* **Status:** Not Run

