# Patient Portal Test Plan

App: [App name or URL]  
Date: [Today’s date]  
Environment: Chrome (desktop), [your OS]

## Scope
Basic smoke tests for login, account, and appointment booking flows.

## Test Cases

1. **Login – valid credentials**
   - Steps: Go to login page, enter valid email/password, click Login.
   - Expected: User is taken to dashboard.

2. **Login – invalid password**
   - Steps: Enter valid email, wrong password, click Login.
   - Expected: Error message shown, user stays on login page.

3. **Appointment booking – all fields valid**
   - Steps: Navigate to Appointments, select date/time, provider, confirm.
   - Expected: Confirmation message and appointment appears in list.

4. **Appointment booking – missing required field**
   - Steps: Leave time or provider blank, try to confirm.
   - Expected: Validation error, appointment not created.

5. **Profile update – valid data**
   - Steps: Go to profile, change phone number, save.
   - Expected: Success message, new value persists on refresh.
