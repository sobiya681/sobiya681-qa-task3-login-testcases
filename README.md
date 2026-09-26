# Task 3: Test Case Design — Login & Password Reset

## Objective
Write and execute 10 detailed test cases covering positive and negative scenarios for a standard User Login & Password Reset module.

## Application Under Test
Figma Login Page — https://figma.com/login

## Tools Used
- Google Sheets (Test Matrix)
- Chrome Browser
- Figma Login Page
- GitHub

## Test Summary
| Metric | Count |
| Total Test Cases | 10 |
| Positive | 5 |
| Negative | 5 |
| Passed | 10 |
| Failed | 0 |

## Test Coverage

### Positive Testing
- Valid login with correct credentials
- Remember Me checkbox session persistence
- Password field input masking
- Password reset link delivery to registered email
- Successful password change via reset link

### Negative Testing
- Login with wrong password
- Login with empty fields
- Login with invalid email format (missing @)
- SQL injection attempt in email field
- Password reset with unregistered email

## Files
- `qa-task3/TestCases_Login_Reset.xlsx` — Full test matrix with 10 test cases
- `qa-task3/screenshots/` — Evidence for executed test cases

## Key Findings
- Login module correctly blocks invalid credentials with proper error messages
- Email validation properly rejects malformed emails and SQL injection attempts
- Password reset flow works end-to-end with confirmation messages
- No security leaks found (no user enumeration on unregistered email reset)

## Author
Sobia
QA Internship: Barakah Tech Labs
