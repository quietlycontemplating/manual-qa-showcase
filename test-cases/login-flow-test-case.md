# 🧪 Test Case: User Login Flow

**Test Case ID:** TC-001  
**Feature:** User Login  
**Test Type:** Functional  
**Priority:** High  
**Created by:** Sharnelle Guthrie  
**Date:** May 26th 2025

---

## 🎯 Objective
To verify that users can successfully log into the platform using valid credentials and receive appropriate errors for invalid input.

---

## ✅ Preconditions
- User has a registered account
- User is on the login page

---

## 🔄 Test Steps

| Step # | Action | Expected Result |
|--------|--------|-----------------|
| 1 | Navigate to the login page | Login form loads with email and password fields |
| 2 | Enter valid email and password | User is redirected to the dashboard |
| 3 | Enter incorrect password | Error message appears: \"Invalid credentials\" |
| 4 | Leave email field blank and submit | Error message appears: \"Email is required\" |
| 5 | Leave password field blank and submit | Error message appears: \"Password is required\" |
| 6 | Enter email in invalid format (e.g., 'abc@') | Error message appears: \"Enter a valid email\" |

---

## 📝 Notes
- Ensure error messages are styled consistently and accessible
- Test on both desktop and mobile if responsive design is enabled


