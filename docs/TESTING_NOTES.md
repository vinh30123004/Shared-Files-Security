# Testing Notes - Shared Files Security

## 1. Testing Objectives

Verify that the Shared Files Security application works correctly and handles invalid inputs safely.

## 2. Testing Scope

- User profile creation.
- Password validation.
- Public key import and export.
- Fingerprint verification.
- File encryption and decryption.
- Digital signature verification.
- Invalid file handling.

## 3. Test Cases

| ID   | Test Scenario                      | Expected Result                  |
| ---- | ---------------------------------- | -------------------------------- |
| TC01 | Create profile with valid password | Profile created successfully     |
| TC02 | Create profile with short password | Application rejects password     |
| TC03 | Import valid public key            | Public key imported successfully |
| TC04 | Verify incorrect fingerprint       | Verification rejected            |
| TC05 | Encrypt a valid file               | Encrypted file generated         |
| TC06 | Decrypt a valid file               | Original file restored           |
| TC07 | Modify encrypted file              | Integrity verification fails     |
| TC08 | Decrypt using wrong recipient      | Decryption rejected              |

## 4. Testing Types

- Functional Testing
- Negative Testing
- Integration Testing
- Security Testing
- Regression Testing

## 5. Test Status

Test results will be recorded as:

- PASS
- FAIL
- BLOCKED
- NOT RUN

Note: These are planned test cases. Actual results must be recorded after execution.
