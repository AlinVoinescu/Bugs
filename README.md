# Bug Samples

Below are some Bug Samples that I wrote while I working on previous project.

------------------

**Priority & Severity:**<br>
P2 - High

**Description:**<br>
When trying to login with correct credentials, nothing happens. The user is not logged in and no error message is displayed.

**Steps to reproduce:**<br>
1.Go to www.website.com/login<br>
2.Add a correct user/pass

**Expected result:**<br>
User should be able to login and is taken to his profile page.

**Actual result:**<br>
User is not logged and no error appears.

**Test data:**
User:alin & Pass:123456

------------------

**Priority & Severity:**<br>
P1 - Critical

**Description:**<br>
When trying to log in on XYZ Bank , no password is required for any account.

**Steps to reproduce:**<br>
1.Go to XYZ Bank  
2.Select an account<br>
3.Try to log in

**Expected result:**<br>
User should be able to log in with user and password.

**Actual result:**<br>
No password is required.

**Test data:**<br>
”Harry Potter”

------------------

**Priority & Severity:**<br>
P1 - Critical

**Description:**<br>
When trying to go to OWASP Juice Shop and I want to pay with a credit card, the expiry year of my credit card start from 2080.

**Steps to reproduce:**<br>
1.Go to OWASP Juice Shop<br> 
2.Select “Add to cart” for some products<br>
3.Select “Pay with Credit Card”<br>
4.Complete “Credit Card” fields 

**Expected result:**<br>
The app should show the expiry year start from 2022.

**Actual result:**<br>
The app show the expiry year start from 2080.

------------------

**Priority & Severity:**<br>
P3 - Normal

**Description:**<br>
When trying to go to www.demoblaze.com/ and write few different letters after the “/” , error 404 message is displayed.

**Steps to reproduce:**<br>
1.Go to www.demoblaze.com/<br> 
2.Type 4 different letters after the “/”

**Expected result:**<br>
User should be able to view the normal page without errors.

**Actual result:**<br>
404 error page appears.

**Test data:**<br>
”fdsa”

------------------

**Priority & Severity:**<br>
P3 - Normal

**Description:**<br>
When trying to go to Home - Primaria Techirghiol  and press “Info-Turism-Cazare” Button and there are broken links.

**Steps to reproduce:**<br>
1.Go to Home - Primaria Techirghiol<br> 
2.Press “Home” button<br>
3.Press “Info tursim” button<br>
4.Press “Cazare” button<br>
5.Select a link

**Expected result:**<br>
User should be redirected to a correct page.

**Actual result:**<br>
404 error apeear.

**Test data:**<br>
"Pensiunea Marea Neagra link"<br>
"Vila Bella link"
