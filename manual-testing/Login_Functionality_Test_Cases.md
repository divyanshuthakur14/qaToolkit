# Login Functionality Test Cases

| Test Case ID | Test Description               | Steps to Execute                                  | Expected Result                      | Status  |
|--------------|-------------------------------|--------------------------------------------------|------------------------------------|---------|
| TC001        | Verify login with valid inputs | 1. Open login page<br>2. Enter valid username and password<br>3. Click login button | User should be successfully logged in and redirected to dashboard | Pass/Fail |
| TC002        | Verify login with invalid password | 1. Open login page<br>2. Enter valid username and invalid password<br>3. Click login button | Error message “Invalid credentials” should be displayed | Pass/Fail |
| TC003        | Verify login with empty fields | 1. Open login page<br>2. Leave username and password fields empty<br>3. Click login button | Error message “Username and password required” should be displayed | Pass/Fail |

