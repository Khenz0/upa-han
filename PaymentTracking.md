# Payment Tracking
This feature is used to enable landlords to track and monitor payment activities in real-time.

## Input
* The landlord shall initiate the request to view real-time payment information.

## Process:
* The landlord shall retrieve and display real-time payment information for each tenant.
* The system shall update the payment statuses dynamically.

## Output:
* The payment dashboard is updated with the latest payment information.

## Data Dictionary
| Element ID | Element Text | Element Type | Data Type | Required | Rules |
| --- | --- | --- | --- | --- | --- |
| tenant_ID | Tenant ID | Tenant Information | Integer | Yes |Auto-incremented, unique identifier for each tenant. |
| tenant_name | Tenant Name | Tenant Information | Text | Yes | Maximum length of 100 characters. |
| payment_date | Payment Date | Payment Details for Tenants | Date | Yes |   |
