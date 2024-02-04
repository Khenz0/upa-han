# Management of Tenant Accounts
This feature is used to facilitate easy management and updates for tenant accounts.

## Features
* Add Tenant
* Edit Tenant
* Remove Tenant

## Input
* Landlords shall initiate actions to manage and update tenant accounts.

## Process
* Landlords shall add, edit, or delete tenant information.
* Landlords shall initiate actions to manage and update tenant accounts.

## Output
* Tenant account information is updated, and notifications are sent accordingly.

## Data Dictionary
| Element ID | Element Text | Element Type | Data Type | Required | Rules |
| --- | --- | --- | --- | --- | --- |
| tenant_ID | Tenant ID | Tenant Information | Integer | Yes |Auto-incremented, unique identifier for each tenant. |
| tenant_name | Tenant Name | Tenant Information | Text | Yes | Maximum length of 100 characters. |
| tenant_contactInfo | Tenant Contact Number | Tenant Information | Text | Yes | Number is Philippine Standard(+63) and only contains elements from 0-9 and a ‘+’. |
| payment_date | Payment Date | Payment Details for Tenants | Date | Yes |   |
| saveButton | Save | Button |   | Yes |   |
| editButton | Edit | Button |   | Yes |   |
| removeButton | Delete | Button |   | Yes |   |
