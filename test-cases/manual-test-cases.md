OrangeHRM Login Test Cases

Website: https://opensource-demo.orangehrmlive.com/

TC01 - Login with correct details

Steps:

1. Open the OrangeHRM website.
2. Enter the correct username and password.
3. Click the Login button.

Expected Result: Dashboard should open after successful login.

Priority: High

TC02 - Login with wrong password

Steps:

1. Open the login page.
2. Enter the correct username and a wrong password.
3. Click the Login button.

Expected Result: Login should fail and an error message should appear.

Priority: High

TC03 - Login with wrong username

Steps:

1. Enter a wrong username and password.
2. Click the Login button.

Expected Result: User should not be able to log in.

Priority: High

TC04 - Login without entering any details

Steps:

1. Leave the username and password fields empty.
2. Click the Login button.

Expected Result: Login should not be successful.

Priority: High

TC05 - Login without username

Steps:

1. Leave the username field empty.
2. Enter a password.
3. Click the Login button.

Expected Result: User should not be able to log in.

Priority: High

TC06 - Login without password

Steps:

1. Enter a username.
2. Leave the password field empty.
3. Click the Login button.

Expected Result: User should not be able to log in.

Priority: High

TC07 - Login using only spaces

Steps:

1. Enter spaces in the username field.
2. Enter spaces in the password field.
3. Click the Login button.

Expected Result: User should not be able to log in using spaces.

Priority: Medium

TC08 - Logout from the application

Steps:

1. Log in using the correct username and password.
2. Click the profile menu.
3. Select Logout.
4. Try opening the Dashboard again.

Expected Result: User should be logged out and should not be able to access the Dashboard without logging in again.

Priority: High
