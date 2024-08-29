# ecore
QA assessment - Test Cases

**Non-Functional Tests**

Test Data:

- https://automation-sandbox-python-mpywqjbdza-uc.a.run.app
- Username: demouser
- Password: abc123
- Browsers: Chrome, Edge, Chrome Mobile


# Test Cases of Log In feature:

**Title: TC022 - Failed Login when navigating the web browser back button - Chrome**

- Prerequisite: After hit the back button, login failed with wrong credentials, the application shows the message: Wrong username or password
- Description: Check the application is not accepting invalid login credentials
- Expected behavior: the application displays error message
- Actual behavior: the application is successfully permiting the log in 
- Priority: 3
- Type: **Non-Functional**
-Status: **FAIL**
- Environment: QA/Pre-Prod
- Browser: Chrome  
- Steps (BDD format):

> - Given I am logged in the web application
> - And click the back button of the browser
> - When I inform invalid Username and password 
> - Then it displays the message: Wrong username or password

**Title: TC023 - Failed Login when navigating the web browser back button - Edge**

- Prerequisite: After hit the back button, login failed with wrong credentials, the application shows the message: Wrong username or password
- Description: Check the application is not accepting invalid login credentials
- Expected behavior: the application displays error message
- Actual behavior: the application is successfully permiting the log in 
- Priority: 3
- Type: **Non-Functional**
- Status: **FAIL**
- Environment: QA/Pre-Prod
- Browser: Chrome  
- Steps (BDD format):

> - Given I am logged in the web application
> - And click the back button of the browser
> - When I inform invalid Username and password 
> - Then it displays the message: Wrong username or password

**Title: TC024 - Failed Login when navigating the web browser back button - Chrome Mobile**

- Prerequisite: After hit the back button, login failed with wrong credentials, the application shows the message: Wrong username or password
- Description: Check the application is not accepting invalid login credentials
- Expected behavior: the application displays error message
- Actual behavior: the application is successfully permiting the log in 
- Priority: 3
- Type: **Non-Functional**
- Status: **FAIL**
- E nvironment: QA/Pre-Prod
- Browser: Chrome  
- Steps (BDD format):

> - Given I am logged in the web application
> - And click the back button of the browser
> - When I inform invalid Username and password 
> - Then it displays the message: Wrong username or password



