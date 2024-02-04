# Efficient Order Processing
This feature is used to ensure the efficient processing of customer payment transactions.

## Input
Tenants shall initiate payment transactions through the mobile app.

## Process
* The system shall process payment transactions securely.
* Real-time updates shall be provided on the status of payment processing.

## Output
* Payment transactions are completed, and both tenants and landlords receive confirmations.

## Data Dictionary
| Element ID | Element Text | Element Type | Data Type | Required | Rules |
| --- | --- | --- | --- | --- | --- |
| logInHeader | Log-in as Tenant or Log-in as Landlord | Header |   |   |   |
| signUpHeader | Sign-up as Tenant or Sign-up as Landlord | Header |   |   |   |
| logInButton | Log-in | Button |   | Yes | Existing Accounts |
| signUpButton | Sign-up | Button |   | Yes | Must follow the requirements in order to sign-up. |
| tenant_ID | Tenant ID | Tenant Information | Integer | Yes |Auto-incremented, unique identifier for each tenant. |
| landowner_id | Landowner ID | Owner Information | Integer | Yes |   |
| paymentHeader | Payment | Header |   |   |   |
| payment_amount | Payment Amount | Payment Details | Decimal | Yes |   |
| payment_refNum | Payment Reference Number | Payment Details | Text | Yes |   |
| paymentButton | Pay Rent | Button |   | Yes |   |
