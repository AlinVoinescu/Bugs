# Bug Samples

Below are some Bug Samples that I wrote while I working on previous project.

------------------

**Priority & Severity:**

P2 - High

**Description:**

When trying to login with correct credentials, nothing happens. The user is not logged in and no error message is displayed.

**Steps to reproduce:**

1.Go to www.website.com/login
2.Add a correct user/pass

**Expected result:**

User should be able to login and is taken to his profile page.

**Actual result:**

User is not logged and no error appears.

**Test data:**

User:alin & Pass:123456

------------------

**Priority & Severity:**

P1 - Critical

**Description:**

When trying to log in on XYZ Bank , no password is required for any account.

**Steps to reproduce:**

1.Go to XYZ Bank  
2.Select an account
3.Try to log in

**Expected result:**

User should be able to log in with user and password.

**Actual result:**

No password is required.

**Test data:**

”Harry Potter”

------------------

**Priority & Severity:**

P1 - Critical

**Description:**

When trying to go to OWASP Juice Shop and I want to pay with a credit card, the expiry year of my credit card start from 2080.

**Steps to reproduce:**

1.Go to OWASP Juice Shop 
2.Select “Add to cart” for some products
3.Select “Pay with Credit Card”
4.Complete “Credit Card” fields 

**Expected result:**

The app should show the expiry year start from 2022.

**Actual result:**

The app show the expiry year start from 2080.

------------------

**Priority & Severity:**

P3 - Normal

**Description:**

When trying to go to www.demoblaze.com/ and write few different letters after the “/” , error 404 message is displayed.

**Steps to reproduce:**

1.Go to www.demoblaze.com/ 
2.Type 4 different letters after the “/”

**Expected result:**

User should be able to view the normal page without errors.

**Actual result:**

404 error page appears.

**Test data:**

”fdsa”

