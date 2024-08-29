# ecore
QA assessment - Test Cases 

**Functional Tests**

Test Data:

- https://automation-sandbox-python-mpywqjbdza-uc.a.run.app
- Username: demouser
- Password: abc123
- Browsers: Chrome, Edge, Chrome Mobile


# Test Cases of Log In feature:

**Title: TC001 - Successfull Login to the Invoice list page - Chrome**

- Prerequesite: After a successful login, the application should redirect the user to the page Invoice List
- Description: Check the application is accepting valid login credential
- Expected behavior: the application displays the invoice list page after the login succeeds
- Actual behavior: the invoice list page is successfully being displayed after the login succeeds
- Priority: 2
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome
- Steps (BDD format): 

> Given I am in the web page
> When I inform valid Username and password 
> Then I am successfully redirected to the Invoice List  

**Title: TC002 - Successfull Login to the Invoice list page - Edge**

- Prerequesite: After a successful login, the application should redirect the user to the page Invoice List
- Description: Check the application is accepting valid login credential
- Expected behavior: the application displays the invoice list page after the login succeeds
- Actual behavior: the invoice list page is successfully being displayed after the login succeeds
- Priority: 2
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge
- Steps (BDD format): 

> - Given I am in the web page
> - When I inform valid Username and password 
> - Then I am successfully redirected to the Invoice List  

**Title: TC003 - Successfull Login to the Invoice list page - Chrome Mobile**

- Prerequesite: After a successful login, the application should redirect the user to the page Invoice List
- Description: Check the application is accepting valid login credential
- Expected behavior: the application displays the invoice list page after the login succeeds
- Actual behavior: the invoice list page is successfully being displayed after the login succeeds
- Priority: 2
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile
- Steps (BDD format): 

> - Given I am in the web page
> - When I inform valid Username and password 
> - Then I am successfully redirected to the Invoice List  

**Title: TC004 - Failed Login to the Invoice list page - Chrome**

- Prerequisite: After a failed login, the application shows the message: Wrong username or password
- Description: Check the application is not accepting invalid login credentials
- Expected behavior: the application displays error message
- Actual behavior: the application displays error message 
- Priority: 2
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome 
- Steps (BDD format):

> - Given I am in the web page
> - When I inform invalid Username and password 
> - Then it displays the message: Wrong username or password

**Title: TC005 - Failed Login to the Invoice list page - Edge**

- Prerequisite: After a failed login, the application shows the message: Wrong username or password
- Description: Check the application is not accepting invalid login credentials
- Expected behavior: the application displays error message
- Actual behavior: the application displays error message 
- Priority: 2
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge 
- Steps (BDD format):

> - Given I am in the web page
> - When I inform invalid Username and password 
> - Then it displays the message: Wrong username or password

**Title: TC006 - Failed Login to the Invoice list page - Chrome Mobile**

- Prerequisite: After a failed login, the application shows the message: Wrong username or password
- Description: Check the application is not accepting invalid login credentials
- Expected behavior: the application displays error message
- Actual behavior: the application displays error message 
- Priority: 2
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile 
- Steps (BDD format):

> - Given I am in the web page
> - When I inform invalid Username and password 
> - Then it displays the message: Wrong username or password


# Test Cases of Invoice Link feature:

**Title: TC007 - Invoice Details link working properly - Chrome**

- Prerequisite: After the user clicks any Invoice Details link, the application opens the Invoice Details screen.
- Description: Check the Invoice Details screen is being successfully displayed
- Expected behavior: Invoice Details screen being displayed properly  
- Actual behavior: Invoice Details screen being displayed properly   
- Priority: 1
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome  
- Steps (BDD format):

> - Given I am logged in the application
> - When I select a Invoice Details in the Invoice Link column 
> - Then the Invoice screen is successfully displayed

**Title: TC008 - Invoice Details link working properly - Edge**

- Prerequisite: After the user clicks any Invoice Details link, the application opens the Invoice Details screen.
- Description: Check the Invoice Details screen is being successfully displayed
- Expected behavior: Invoice Details screen being displayed properly  
- Actual behavior: Invoice Details screen being displayed properly   
- Priority: 1
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge  
- Steps (BDD format):

> - Given I am logged in the application
> - When I select a Invoice Details in the Invoice Link column 
> - Then the Invoice screen is successfully displayed

**Title: TC009 - Invoice Details link working properly - Chrome Mobile** 

- Prerequisite: After the user clicks any Invoice Details link, the application opens the Invoice Details screen.
- Description: Check the Invoice Details screen is being successfully displayed
- Expected behavior: Invoice Details screen being displayed properly  
- Actual behavior: Invoice Details screen being displayed properly   
- Priority: 1
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile  
- Steps (BDD format):

> - Given I am logged in the application
> - When I select a Invoice Details in the Invoice Link column 
> - Then the Invoice screen is successfully displayed




