# 🛒 Exploratory Testing Checklist – Checkout Flow

**Checklist ID:** XC-002  
**Feature:** E-commerce Checkout  
**Created by:** Sharnelle Guthrie  
**Date:** May 26th 2025  
**Test Type:** Exploratory  
**Priority:** High  

---

## 🎯 Goal

Explore the checkout process to identify friction points, usability issues, and validation failures that could prevent users from completing a purchase.

---

## ✅ Core Functionality

- [ ] Cart correctly displays selected items and quantities  
- [ ] Checkout button works from cart  
- [ ] Shipping and billing address forms are visible  
- [ ] Payment method selection is available  
- [ ] Order confirmation is shown after payment submission  

---

## 🛡️ Field Validations

- [ ] Required fields block submission if left blank  
- [ ] Invalid credit card numbers are rejected  
- [ ] Expired cards show an appropriate error  
- [ ] Postal codes are validated (optional by country)  
- [ ] Email format is enforced for receipts  

---

## 🔁 Edge Cases

- [ ] Try submitting with only partial data filled  
- [ ] Paste invalid characters into card number fields  
- [ ] Attempt checkout with an empty cart  
- [ ] Submit multiple times in a row  
- [ ] Refresh page mid-checkout—does data persist?

---

## 📱 UX & Responsive Behavior

- [ ] All form fields are accessible on mobile  
- [ ] Tab key moves logically through fields  
- [ ] Error messages are easy to read and close  
- [ ] Load time is reasonable between steps  
- [ ] Keyboard doesn’t block CTA buttons on mobile

---

## 🧠 Notes

- Does the user receive a confirmation email or receipt?
- Is there a loading indicator during processing?
- Can guest users check out, or is login required?
- Are tracking links required at checkout, or will they be emailed?

