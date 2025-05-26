# 🔐 Test Case: Password Reset Flow

**Test Case ID**: TC-002  
**Feature**: Password Reset  
**Test Type**: Functional  
**Priority**: High  
**Created by**: Sharnelle Guthrie  
**Date**: [Today’s date]

---

## 🎯 Objective

To verify that users can reset their password using the "Forgot Password" functionality and receive appropriate feedback for both valid and invalid input.

---

## ✅ Preconditions

- User has an existing account
- User is on the login page

---

## 📋 Test Steps

1. Click on the “Forgot Password” link on the login page  
2. Enter a **registered email address** in the reset form  
3. Submit the form  
4. Check for confirmation message or email delivery  
5. Open the email and click the password reset link  
6. Enter a new password and confirm it  
7. Submit the new password  
8. Attempt login with the new password  

---

## 🔍 Negative Test Scenarios

- Enter an **unregistered email** → Verify error message  
- Leave email field blank → Verify validation error  
- Submit mismatched passwords → Verify mismatch warning  
- Enter weak password (e.g., “123”) → Verify password strength requirement  
- Reuse old password → Verify if system blocks reuse (if applicable)

---

## ✅ Expected Results

- User receives confirmation message after submitting a valid email  
- Password reset email is delivered within a reasonable time  
- Reset link redirects to secure password form  
- User is able to successfully log in with the new password  
- Errors are displayed clearly for all invalid scenarios
