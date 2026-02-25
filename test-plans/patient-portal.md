# Patient Portal Test Plan

**App:** Zocdoc.com 
**Tester:** Ben P  
**Date:** February 25, 2026  
**Environment:** Chrome 122, Windows 11

## Test Objective
Verify core patient portal functionality: login, appointment booking, profile management.

## Test Cases

**TC-001: Login - Valid Credentials**
- Navigate to login page
- Enter valid email/password  
- Click "Login"
- **Expected:** Redirect to dashboard

**TC-002: Login - Invalid Password**
- Enter valid email, incorrect password
- Click "Login"  
- **Expected:** Error message, remain on login page

**TC-003: Book Appointment - Complete Flow**
- Login → Appointments → Select provider → Date → Time → Confirm
- **Expected:** Confirmation page, appointment in list

**TC-004: Book Appointment - Missing Required Field**
- Skip provider selection → Attempt confirm
- **Expected:** Validation error, appointment not created

**TC-005: Profile Update - Phone Number**
- Profile → Edit phone → Save
- Refresh page
- **Expected:** New phone number displays
