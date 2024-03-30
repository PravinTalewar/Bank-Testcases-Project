# Project Title: New User Account Opening System

## Description
This project aims to validate the functionality of opening a new user account in our system. It includes various test scenarios covering new user registration, account details, customer details, document verification, and Aadhar OTP functionality.

## Test Cases Overview

### TC_NU_01: New User Functionality - Open Saving Account
- **Precondition:** If new user, open saving account.
- **Test Steps:**
  - Click on "New User?"
  - Open saving account.
- **Expected Result:** Navigate to the account details screen.

### TC_AD_02: New User Functionality - Account Details
- **Precondition:** Not applicable.
- **Test Steps:**
  - Enter account details.
  - Select all mandatory options and click "Next".
- **Expected Result:** Navigate to the customer details screen.

### TC_CD_03: New User Functionality - Customer Details
- **Precondition:** Not applicable.
- **Test Steps:**
  - Enter customer details.
  - Enter all mandatory options and click "Next".
- **Expected Result:** Navigate to the customer details screen with checkboxes.

### TC_CD_04: New User Functionality - Customer Details Screen with Checkbox
- **Precondition:** Not applicable.
- **Test Steps:**
  - Click on checkboxes.
- **Expected Result:** Able to check/uncheck boxes and proceed to the next screen.

### TC_CD_05: New User Functionality - Customer Details Screen without Checkbox
- **Precondition:** Not applicable.
- **Test Steps:**
  - Click without checkboxes.
- **Expected Result:** Unable to proceed without selecting checkboxes.

### TC_DD_06: New User Functionality - Validate Customer Documents Details
- **Precondition:** Not applicable.
- **Test Steps:**
  - Enter customer document details.
  - Click "Next".
- **Expected Result:** Navigate to Aadhar OTP verification screen.

### TC_AO_07: Aadhar OTP Functionality - Aadhar OTP Verification
- **Precondition:** Enter valid mobile number.
- **Test Steps:**
  - Enter OTP sent to mobile number.
  - Submit.
- **Expected Result:** OTP submitted successfully.

### TC_AO_08: Aadhar OTP Functionality - Aadhar OTP Verification (Resend Option)
- **Precondition:** Enter valid mobile number.
- **Test Steps:**
  - Wait for OTP.
  - Resend OTP.
- **Expected Result:** OTP resent successfully.

## Status
All test cases have been executed and passed successfully.

For more detailed test case execution reports and logs, refer to the respective test case documents.

