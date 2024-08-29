# ecore
QA assessment - Test Cases

**Regression Tests**

Test Data:

- https://automation-sandbox-python-mpywqjbdza-uc.a.run.app
- Username: demouser
- Password: abc123
- Browsers: Chrome, Edge, Chrome Mobile


# Test Cases of Invoice Details feature:

**Title: TC010 - Invoice dates displayed on Invoice Details screen - Chrome** 

- Prerequisite: Invoice Date and Due Date are displayed on the Invoice Details screen.
- Description: Check the Invoice Details screen is displaying the dates properly
- Expected behavior: Invoice Details dates displayed properly  
- Actual behavior:  Invoice Details dates displayed properly    
- Priority: 1
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select a Invoice Details in the Invoice Link column 
> - Then the Invoice date and due date are successfully displayed in the Hotel name section

**Title: TC011 - Invoice dates displayed on Invoice Details screen - Edge**

- Prerequisite: Invoice Date and Due Date are displayed on the Invoice Details screen.
- Description: Check the Invoice Details screen is displaying the dates properly
- Expected behavior: Invoice Details dates displayed properly  
- Actual behavior:  Invoice Details dates displayed properly    
- Priority: 1
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then the Invoice date and due date are successfully displayed in the Hotel name section

**Title: TC012 - Invoice dates displayed on Invoice Details screen - Chrome Mobile**

- Prerequisite: Invoice Date and Due Date are displayed on the Invoice Details screen.
- Description: Check the Invoice Details screen is displaying the dates properly
- Expected behavior: Invoice Details dates displayed properly  
- Actual behavior:  Invoice Details dates displayed properly    
- Priority: 1
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile  
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then the Invoice date and due date are successfully displayed in the Hotel name section

**Title: TC013 - Booking details on Invoice Details screen - Chrome**

- Prerequisite: Informations of the reservation are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the dates properly
- Expected behavior: Booking information displayed properly  
- Actual behavior:  Booking information displayed properly     
- Priority: 1
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then every Booking data below scheme are successfully displayed in the Booking/Stay section

> - Booking Code | Room	| Total Stay Count | Total Stay Amount | Check-In | Check-Out

**Title: TC014 - Booking details on Invoice Details screen - Edge**

- Prerequisite: Informations of the reservation are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the dates properly
- Expected behavior: Booking information displayed properly  
- Actual behavior:  Booking information displayed properly     
- Priority: 1
- Type: **Regression**
-Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then every Booking data below scheme are successfully displayed in the Booking/Stay section

> - Booking Code | Room	| Total Stay Count | Total Stay Amount | Check-In | Check-Out

**Title: TC015 - Booking details on Invoice Details screen - Chrome Mobile**

- Prerequisite: Informations of the reservation are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the dates properly
- Expected behavior: Booking information displayed properly  
- Actual behavior:  Booking information displayed properly     
- Priority: 1
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile  
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then every Booking data below scheme are successfully displayed in the Booking/Stay section

> - Booking Code | Room	| Total Stay Count | Total Stay Amount | Check-In | Check-Out

**Title: TC016 - Customer Details on Invoice Details screen - Chrome**

- Prerequisite: Name and address of the customer are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the customer informations properly
- Expected behavior: Customer information displayed properly  
- Actual behavior:  Customer information displayed properly     
- Priority: 1
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then the name and address of the customer are successfully displayed in the Customer Details section

**Title: TC017 - Customer Details on Invoice Details screen - Edge**

- Prerequisite: Name and address of the customer are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the customer informations properly
- Expected behavior: Customer information displayed properly  
- Actual behavior:  Customer information displayed properly     
- Priority: 1
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then the name and address of the customer are successfully displayed in the Customer Details section

**Title: TC018 - Customer Details on Invoice Details screen - Chrome Mobile**

- Prerequisite: Name and address of the customer are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the customer informations properly
- Expected behavior: Customer information displayed properly  
- Actual behavior:  Customer information displayed properly     
- Priority: 1
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile   
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then the name and address of the customer are successfully displayed in the Customer Details section

**Title: TC019 - Billing Details on Invoice Details screen - Chrome**  

- Prerequisite: Billing data are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the billing informations properly
- Expected behavior: Billing information displayed properly  
- Actual behavior:  Billing information displayed properly     
- Priority: 1
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome    
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then every Billing data below scheme are successfully displayed in the Billing Details section

> - Deposit Nowt | Tax&VAT | Total Amount

**Title: TC020 - Billing Details on Invoice Details screen - Edge**

- Prerequisite: Billing data are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the billing informations properly
- Expected behavior: Billing information displayed properly  
- Actual behavior:  Billing information displayed properly     
- Priority: 1
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Edge    
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then every Billing data below scheme are successfully displayed in the Billing Details section

> - Deposit Nowt | Tax&VAT | Total Amount

**Title: TC021 - Billing Details on Invoice Details screen - Chrome Mobile**

- Prerequisite: Billing data are displayed on the Invoice Details.
- Description: Check the Invoice Details screen is displaying the billing informations properly
- Expected behavior: Billing information displayed properly  
- Actual behavior:  Billing information displayed properly     
- Priority: 1
- Type: **Regression**
- Status: PASS
- Environment: QA/Pre-Prod
- Browser: Chrome Mobile    
- Steps (BDD format):

> - Given I am logged in the application
> - When I select an Invoice Details in the Invoice Link column 
> - Then every Billing data below scheme are successfully displayed in the Billing Details section

> - Deposit Nowt | Tax&VAT | Total Amount


