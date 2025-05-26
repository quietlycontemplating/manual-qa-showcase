# 🧪 Exploratory Testing Checklist – Contact Form

**Checklist ID:** XC-001  
**Feature:** Website Contact Form  
**Created by:** Sharnelle Guthrie  
**Date:** [Insert today’s date]  
**Test Type:** Exploratory  
**Priority:** Medium  

---

## 🔍 Goal

Explore the contact form functionality to identify potential usability issues, error handling gaps, or missing validations.

---

## ✅ Basic Functionality

- [ ] Form loads correctly on desktop  
- [ ] Form loads correctly on mobile  
- [ ] All input fields are visible and labeled  
- [ ] Submit button is present and active  
- [ ] Confirmation message or redirect appears after submission  

---

## 🛡️ Field Validations

- [ ] Email field requires valid format (e.g., `name@domain.com`)  
- [ ] Required fields trigger an error if left blank  
- [ ] Phone number accepts only digits (if present)  
- [ ] Character limits are enforced (e.g., message box)  
- [ ] Error messages are clear and specific  

---

## 🔁 Edge Cases

- [ ] Submit with only partial fields filled  
- [ ] Paste invalid input into fields  
- [ ] Submit with excess characters in message  
- [ ] Submit repeatedly (spam attempt)  
- [ ] Try with no internet connection  

---

## 📱 Responsive + UX

- [ ] Fields are readable on mobile  
- [ ] Keyboard doesn’t block fields on mobile  
- [ ] Focus auto-jumps between fields where expected  
- [ ] Submit button has hover/focus states  

---

## 🧠 Notes

- Could use auto-confirmation via email?  
- Consider rate limiting for spam prevention  

