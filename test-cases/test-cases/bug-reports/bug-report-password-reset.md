# 🐞 Bug Report: Password Reset – Invalid Email Error Missing

**Bug ID:** BR-001  
**Reported By:** Sharnelle Guthrie  
**Date:** May 26th 2025  
**Environment:** Web (Production)  
**Priority:** Medium  
**Status:** Open

---

## 🔍 Summary

The system does not display an error message when an unregistered email address is submitted on the "Forgot Password" form. This may confuse users or create the false impression that the password reset email was sent.

---

## 🎯 Steps to Reproduce

1. Navigate to the Login Page.
2. Click on the "Forgot Password" link.
3. Enter an **unregistered** email address (e.g., notintheirrecords@example.com).
4. Click "Send" or "Reset Password".

---

## ❌ Expected Result

An error message should appear saying something like:  
**“This email address is not registered. Please try again or sign up.”**

---

## ✅ Actual Result

The form refreshes with no visible error or confirmation. No password reset email is sent.

---

## 📸 Screenshots / Video

_N/A for now — you can add one later if you simulate it._

---

## 💬 Notes

- Issue was reproducible in Chrome and Firefox.
- May impact user trust or lead to unnecessary support tickets.


