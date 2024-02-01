# Notification System
This feature automatically alerts landowners and tenants through notifications about tenants with due/overdue rental payments.

## Input:
* The system database contains tenant information, payment details, and due dates.
* A predefined threshold or condition indicating that a payment is due/overdue.

## Process:
* The system monitors the payment due dates for all tenants.
* Identify tenants whose payments are overdue based on the threshold criteria.
* Generate notifications for the identified overdue payments.
* Determine the recipients for notifications.
* Send notifications to the identified recipients.

## Output:
* A notification is sent to the relevant landowners and tenants, informing them of due/overdue payments.
* Maintain a log of notifications sent, including details such as notification ID, recipient, timestamp, and related payment information.

## Data Dictionary
