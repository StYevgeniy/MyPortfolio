# QA Portfolio – Yevgeniy Storozhenko

---

## 🔷 1. Test Cases

### Module: User Registration

**TC-01 – Successful registration**

* Preconditions: User is on registration page
* Steps:

  1. Enter valid email
  2. Enter valid password
  3. Click Register
* Expected Result: User is registered successfully

**TC-02 – Invalid email format**

* Steps:

  1. Enter "test@"
  2. Submit
* Expected Result: Validation error displayed

**TC-03 – Empty fields submission**

* Steps: Click Register without filling fields
* Expected Result: Required field errors

**TC-04 – Password too short**

* Steps: Enter password < 6 chars
* Expected Result: Error message

**TC-05 – Existing user registration**

* Steps: Register with already used email
* Expected Result: Error "User already exists"

---

### Module: Login

**TC-06 – Valid login**

* Expected: User logged in

**TC-07 – Invalid password**

* Expected: Error message

**TC-08 – Empty login fields**

* Expected: Validation errors

---

### Module: Form Validation

**TC-09 – Email validation**

* Expected: Only valid format accepted

**TC-10 – Password strength**

* Expected: Weak password rejected

---

### Module: UI / UX

**TC-11 – Button click response**

* Expected: Button reacts visually

**TC-12 – Responsive layout**

* Expected: Correct display on mobile

---

### Module: API Testing

**TC-13 – GET request success**

* Expected: 200 OK

**TC-14 – POST request valid data**

* Expected: 201 Created

**TC-15 – Invalid request data**

* Expected: 400 Bad Request

---

### Module: Edge Cases

**TC-16 – Long input data**

* Expected: System handles correctly

**TC-17 – Special characters input**

* Expected: No crash

**TC-18 – Network interruption**

* Expected: Error handled gracefully

---

### Additional

**TC-19 – Logout functionality**

* Expected: User logged out

**TC-20 – Session expiration**

* Expected: User redirected to login

---

## 🔶 2. Checklist

### Registration Page

* [ ] Page loads correctly
* [ ] Input fields visible
* [ ] Validation works
* [ ] Error messages displayed

### Login Page

* [ ] Login works
* [ ] Error handling

### UI

* [ ] Responsive design
* [ ] Buttons clickable
* [ ] No layout breaks

### API

* [ ] Status codes correct
* [ ] Response format valid

---

## 🔴 3. Bug Reports

### Bug #1 – Email validation missing

* **Severity:** Medium
* **Steps:** Enter invalid email
* **Expected:** Error message
* **Actual:** No validation

---

### Bug #2 – API returns wrong status

* **Severity:** High
* **Steps:** Send invalid request
* **Expected:** 400 error
* **Actual:** 200 OK

---

### Bug #3 – Button not clickable

* **Severity:** Critical
* **Steps:** Click Submit
* **Expected:** Form submitted
* **Actual:** No action

---

### Bug #4 – Layout breaks on mobile

* **Severity:** Medium
* **Steps:** Open on small screen
* **Expected:** Responsive UI
* **Actual:** Elements overlap

---

## 💡 Notes

* All examples are based on real QA practice
* Can be exported to TestRail / CSV
* Can be attached to portfolio website

---
