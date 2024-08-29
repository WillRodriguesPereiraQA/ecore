# ecore
QA assessment - Test Cases


Test Data:

- https://automation-sandbox-python-mpywqjbdza-uc.a.run.app
- Username: demouser
- Password: abc123
- Browsers: Chrome, Edge, Chrome Mobile


**Test Cases of Log In feature:**
# Title: TC001 - Successfull Login to the Invoice list page - Chrome
- Prerequesite: After a successful login, the application should redirect the user to the page Invoice List
- Description: Check the application is accepting valid login credential
- Expected behavior: the application displays the invoice list page after the login succeeds
- Actual behavior: the invoice list page is successfully being displayed after the login succeeds
- Priority: 
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome
- Steps (BDD format): 

> Given I am in the web page
> When I inform valid Username and password 
> Then I am successfully redirected to the Invoice List  

# Title: TC002 - Successfull Login to the Invoice list page - Edge
- Prerequesite: After a successful login, the application should redirect the user to the page Invoice List
- Description: Check the application is accepting valid login credential
- Expected behavior: the application displays the invoice list page after the login succeeds
- Actual behavior: the invoice list page is successfully being displayed after the login succeeds
- Priority:
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge
- Steps (BDD format): 

> - Given I am in the web page
> - When I inform valid Username and password 
> - Then I am successfully redirected to the Invoice List  

# Title: TC003 - Successfull Login to the Invoice list page - Chrome Mobile
- Prerequesite: After a successful login, the application should redirect the user to the page Invoice List
- Description: Check the application is accepting valid login credential
- Expected behavior: the application displays the invoice list page after the login succeeds
- Actual behavior: the invoice list page is successfully being displayed after the login succeeds
- Priority:
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile
- Steps (BDD format): 

> - Given I am in the web page
> - When I inform valid Username and password 
> - Then I am successfully redirected to the Invoice List  

# Title: TC004 - Failed Login to the Invoice list page - Chrome
- Prerequisite: After a failed login, the application shows the message: Wrong username or password
- Description: Check the application is not accepting invalid login credentials
- Expected behavior: the application displays error message
- Actual behavior: the application displays error message 
- Priority:
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome 
- Steps (BDD format):

> - Given I am in the web page
> - When I inform invalid Username and password 
> - Then it displays the message: Wrong username or password

# Title: TC005 - Failed Login to the Invoice list page - Edge
- Prerequisite: After a failed login, the application shows the message: Wrong username or password
- Description: Check the application is not accepting invalid login credentials
- Expected behavior: the application displays error message
- Actual behavior: the application displays error message 
- Priority:
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge 
- Steps (BDD format):

> - Given I am in the web page
> - When I inform invalid Username and password 
> - Then it displays the message: Wrong username or password

# Title: TC006 - Failed Login to the Invoice list page - Chrome Mobile
- Prerequisite: After a failed login, the application shows the message: Wrong username or password
- Description: Check the application is not accepting invalid login credentials
- Expected behavior: the application displays error message
- Actual behavior: the application displays error message 
- Priority:
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile 
- Steps (BDD format):

> - Given I am in the web page
> - When I inform invalid Username and password 
> - Then it displays the message: Wrong username or password


**Test Cases of Invoice Link feature:**
# Title: TC007 - Invoice Details link working properly - Chrome
- Prerequisite: After the user clicks any Invoice Details link, the application opens the Invoice Details screen.
- Description: Check the Invoice Details screen is being successfully displayed
- Expected behavior: Invoice Details screen being displayed properly  
- Actual behavior: Invoice Details screen being displayed properly   
- Priority:
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome  
- Steps (BDD format):

> - Given I am logged in the application
> - When I select a Invoice Details in the Invoice Link column 
> - Then the Invoice screen is successfully displayed

# Title: TC008 - Invoice Details link working properly - Edge
- Prerequisite: After the user clicks any Invoice Details link, the application opens the Invoice Details screen.
- Description: Check the Invoice Details screen is being successfully displayed
- Expected behavior: Invoice Details screen being displayed properly  
- Actual behavior: Invoice Details screen being displayed properly   
- Priority:
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge  
- Steps (BDD format):

> - Given I am logged in the application
> - When I select a Invoice Details in the Invoice Link column 
> - Then the Invoice screen is successfully displayed

# Title: TC009 - Invoice Details link working properly - Chrome Mobile 
- Prerequisite: After the user clicks any Invoice Details link, the application opens the Invoice Details screen.
- Description: Check the Invoice Details screen is being successfully displayed
- Expected behavior: Invoice Details screen being displayed properly  
- Actual behavior: Invoice Details screen being displayed properly   
-Priority:
- Type: **Functional**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile  
- Steps (BDD format):

> - Given I am logged in the application
> - When I select a Invoice Details in the Invoice Link column 
> - Then the Invoice screen is successfully displayed


**Test Cases of Invoice Details feature:**
# Title: TC010 - Invoice dates displayed on Invoice Details screen - Chrome 
- Prerequisite: Invoice Date and Due Date are displayed on the Invoice Details screen.
- Description: Check the Invoice Details screen is displaying the dates properly
- Expected behavior: Invoice Details dates displayed properly  
- Actual behavior:  Invoice Details dates displayed properly    
- Priority: 2
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select a Invoice Details in the Invoice Link column 
> - Then the Invoice date and due date are successfully displayed in the Hotel name section

# Title: TC011 - Invoice dates displayed on Invoice Details screen - Edge
- Prerequisite: Invoice Date and Due Date are displayed on the Invoice Details screen.
- Description: Check the Invoice Details screen is displaying the dates properly
- Expected behavior: Invoice Details dates displayed properly  
- Actual behavior:  Invoice Details dates displayed properly    
- Priority: 2
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then the Invoice date and due date are successfully displayed in the Hotel name section

# Title: TC012 - Invoice dates displayed on Invoice Details screen - Chrome Mobile
- Prerequisite: Invoice Date and Due Date are displayed on the Invoice Details screen.
- Description: Check the Invoice Details screen is displaying the dates properly
- Expected behavior: Invoice Details dates displayed properly  
- Actual behavior:  Invoice Details dates displayed properly    
- Priority: 2
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile  
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then the Invoice date and due date are successfully displayed in the Hotel name section

# Title: TC013 - Booking details on Invoice Details screen - Chrome
- Prerequisite: Informations of the reservation are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the dates properly
- Expected behavior: Booking information displayed properly  
- Actual behavior:  Booking information displayed properly     
- Priority: 2
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then every Booking data below scheme are successfully displayed in the Booking/Stay section

> - Booking Code | Room	| Total Stay Count | Total Stay Amount | Check-In | Check-Out

# Title: TC014 - Booking details on Invoice Details screen - Edge

- Prerequisite: Informations of the reservation are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the dates properly
- Expected behavior: Booking information displayed properly  
- Actual behavior:  Booking information displayed properly     
- Priority: 2
- Type: **Regression**
-Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then every Booking data below scheme are successfully displayed in the Booking/Stay section

> - Booking Code | Room	| Total Stay Count | Total Stay Amount | Check-In | Check-Out

# Title: TC015 - Booking details on Invoice Details screen - Chrome Mobile

- Prerequisite: Informations of the reservation are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the dates properly
- Expected behavior: Booking information displayed properly  
- Actual behavior:  Booking information displayed properly     
- Priority: 2
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile  
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then every Booking data below scheme are successfully displayed in the Booking/Stay section

> - Booking Code | Room	| Total Stay Count | Total Stay Amount | Check-In | Check-Out

# Title: TC016 - Customer Details on Invoice Details screen - Chrome
- Prerequisite: Name and address of the customer are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the customer informations properly
- Expected behavior: Customer information displayed properly  
- Actual behavior:  Customer information displayed properly     
- Priority: 2
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then the name and address of the customer are successfully displayed in the Customer Details section

# Title: TC017 - Customer Details on Invoice Details screen - Edge
- Prerequisite: Name and address of the customer are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the customer informations properly
- Expected behavior: Customer information displayed properly  
- Actual behavior:  Customer information displayed properly     
- Priority: 2
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then the name and address of the customer are successfully displayed in the Customer Details section

# Title: TC018 - Customer Details on Invoice Details screen - Chrome Mobile
- Prerequisite: Name and address of the customer are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the customer informations properly
- Expected behavior: Customer information displayed properly  
- Actual behavior:  Customer information displayed properly     
- Priority: 2
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then the name and address of the customer are successfully displayed in the Customer Details section

# Title: TC019 - Billing Details on Invoice Details screen - Chrome  
- Prerequisite: Billing data are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the billing informations properly
- Expected behavior: Billing information displayed properly  
- Actual behavior:  Billing information displayed properly     
- Priority: 2
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome    
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then every Billing data below scheme are successfully displayed in the Billing Details section

> - Deposit Nowt | Tax&VAT | Total Amount

# Title: TC020 - Billing Details on Invoice Details screen - Edge 
- Prerequisite: Billing data are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the billing informations properly
- Expected behavior: Billing information displayed properly  
- Actual behavior:  Billing information displayed properly     
- Priority: 2
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge    
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then every Billing data below scheme are successfully displayed in the Billing Details section

> - Deposit Nowt | Tax&VAT | Total Amount

# Title: TC021 - Billing Details on Invoice Details screen - Chrome Mobile 
- Prerequisite: Billing data are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the billing informations properly
- Expected behavior: Billing information displayed properly  
- Actual behavior:  Billing information displayed properly     
- Priority: 2
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile    
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then every Billing data below scheme are successfully displayed in the Billing Details section

> - Deposit Nowt | Tax&VAT | Total Amount


**Test Cases of Log In feature:**
# Title: TC022 - Failed Login when navigating the web browser back button - Chrome
- Prerequisite: After hit the back button, login failed with wrong credentials, the application shows the message: Wrong username or password
- Description: Check the application is not accepting invalid login credentials
- Expected behavior: the application displays error message
- Actual behavior: the application is successfully permiting the log in 
- Priority: 1
- Type: **Non-Functional**
-Status: **FAIL**
- Environment: QA/Pre-Prod
- Browser: Chrome  
- Steps (BDD format):

> - Given I am logged in the web application
> - And click the back button of the browser
> - When I inform invalid Username and password 
> - Then it displays the message: Wrong username or password

# Title: TC023 - Failed Login when navigating the web browser back button - Edge
- Prerequisite: After hit the back button, login failed with wrong credentials, the application shows the message: Wrong username or password
- Description: Check the application is not accepting invalid login credentials
- Expected behavior: the application displays error message
- Actual behavior: the application is successfully permiting the log in 
- Priority: 1
- Type: **Non-Functional**
- Status: **FAIL**
- Environment: QA/Pre-Prod
- Browser: Chrome  
- Steps (BDD format):

> - Given I am logged in the web application
> - And click the back button of the browser
> - When I inform invalid Username and password 
> - Then it displays the message: Wrong username or password

# Title: TC024 - Failed Login when navigating the web browser back button - Chrome Mobile
- Prerequisite: After hit the back button, login failed with wrong credentials, the application shows the message: Wrong username or password
- Description: Check the application is not accepting invalid login credentials
- Expected behavior: the application displays error message
- Actual behavior: the application is successfully permiting the log in 
- Priority: 1
- Type: **Non-Functional**
- Status: **FAIL**
- E nvironment: QA/Pre-Prod
- Browser: Chrome  
- Steps (BDD format):

> - Given I am logged in the web application
> - And click the back button of the browser
> - When I inform invalid Username and password 
> - Then it displays the message: Wrong username or password



