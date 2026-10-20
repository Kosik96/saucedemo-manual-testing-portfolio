TC-003 — Login with Empty Username

Test Case Information:

Test Case ID: TC-003

Title: Login with empty Username

Module: Login

Priority: High

Test Type: Negative

Preconditions:

The SauceDemo login page is open.
Test Data:
Username: Empty
Password: secret_sauce

Test Steps:
Leave the Username field empty.
Enter secret_sauce in the Password field.
Click the Login button.

Expected Result:
The login attempt is rejected and a validation message indicates that the Username is required.

Actual Result:
The login attempt was rejected and the application displayed the message “Username is required”.


Status:
PASS

