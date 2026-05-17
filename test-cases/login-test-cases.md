# Login Test Cases

## TC-001: Login with valid credentials

**Preconditions:**  
The user has a registered account.

**Steps:**
1. Open the login page.
2. Enter a valid email.
3. Enter a valid password.
4. Click the Login button.

**Expected Result:**  
The user should be redirected to the dashboard.

**Status:**  
Not executed.

---

## TC-002: Login with invalid password

**Preconditions:**  
The user has a registered account.

**Steps:**
1. Open the login page.
2. Enter a valid email.
3. Enter an invalid password.
4. Click the Login button.

**Expected Result:**  
The system should display an error message indicating that the credentials are incorrect.

**Status:**  
Not executed.

---

## TC-003: Login with empty email field

**Preconditions:**  
The user is on the login page.

**Steps:**
1. Open the login page.
2. Leave the email field empty.
3. Enter a valid password.
4. Click the Login button.

**Expected Result:**  
The system should display a validation message indicating that the email field is required.

**Status:**  
Not executed.

---

## TC-004: Login with empty password field

**Preconditions:**  
The user is on the login page.

**Steps:**
1. Open the login page.
2. Enter a valid email.
3. Leave the password field empty.
4. Click the Login button.

**Expected Result:**  
The system should display a validation message indicating that the password field is required.

**Status:**  
Not executed.

---

## TC-005: Login with empty email and password fields

**Preconditions:**  
The user is on the login page.

**Steps:**
1. Open the login page.
2. Leave the email field empty.
3. Leave the password field empty.
4. Click the Login button.

**Expected Result:**  
The system should display validation messages indicating that the email and password fields are required.

**Status:**  
Not executed.
