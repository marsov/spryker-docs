---
title: Managing main merchant returns
last_updated: Aug 09, 2021
description: This guide explains how to manage main merchant returns in the Back Office.
template: back-office-user-guide-template
---

*My Returns* allows you to manage the returns as follows:

- Create a return for the customer.
- Set the return states.
- Print the return slip.

## Prerequisites

To start managing the returns for the [main merchant](/docs/marketplace/user/features/{{page.version}}/marketplace-merchant-feature-overview/main-merchant-concept.html), navigate to **Sales** > **My Returns**.

Each section contains reference information. Make sure to review it before you start, or just look up the necessary information as you go through the process.

## Viewing returns for the main merchant

To view details on a return, in the *Actions* column of the return, click **View**.

This takes you to the *Overview of Return: [Return reference]* page where you can view the return details, set the return statuses, and [print the return slip](#printing-a-main-merchant-return-slip).

## Setting the main merchant return states

To set and track the return statuses, you trigger the return states.

To trigger the return states:

1. On the *Returns* page, click **View** in the *Actions* column. This takes you to the *Return Overview [Return reference]*.
2. In the *Trigger all matching state section* of the *Overview of Return: [Return reference]* page, click the necessary state. The return state changes and the new states that you can trigger, appear. See Main merchant return item states for information on the return item states and the flow.



**Info**

The triggered return states are reflected in the Customer Account on the Storefront informing customers about the statuses of their returns.

------

**Tips & Tricks**

To trigger the return states for all the items in the return, click the states at the *Trigger all matching states* field. To trigger the return states for individual items of the return, trigger the states in the *Trigger event* column for the necessary items.

------

### Reference information: Setting the main merchant return states

This section holds reference information related to setting the marketplace return states.

#### My Returns page

On the *Returns* page, you see the following:

- Return ID
- Return reference
- Marketplace order reference
- Returned Products (number of the sales order items that were returned)
- Return Date
- State
- Actions

By default, the last created return goes on top of the table. However, you can sort and search the *List of Returns* table.

All columns with headers having arrows in the *My Returns* table are sortable.

##### Actions column

All the return management options that you can invoke from the *Actions* column on the *My Returns* page are described in the following table.

| ACTION     | DESCRIPTION                                                  |
| --------- | ----------------------------------------------------------- |
| View       | Takes you to the *Overview of Return: [Return reference]* page. Here, you can find all the information about the chosen review. |
| Print Slip | Takes you to the print version of the return slip.           |

#### Overview of Return: [Return Reference] page

The following tables describe the attributes on the *Overview of Return: [Return reference]* page when you view a return. 

##### Returned items section

The returned items section displays information on the returned items.

| ATTRIBUTE   | DESCRIPTION       |
| -------------------- | ----------------------------------------- |
| Product  | List of all items included in the return.                    |
| Quantity   | Product quantity.                                            |
| Price  | Product price.                                               |
| Total   | Total amount paid for the item.                              |
| State   | Return state for the item. See Main merchant return states for more details. |
| Trigger event   | List of the events to trigger for the return.                |
| Trigger all matching states | States that you can trigger for all items in the return at once. |

##### Total section

The Total section displays the total amount of items to be returned.

##### General information section

| ATTRIBUTE                   | DESCRIPTION                                  |
| ------------------------- | ------------------------------------ |
| Order Reference             | Reference number of the main merchant order. |
| Marketplace order reference | Reference number of the marketplace order.   |
| Return Reference            | Reference number of the return.              |
| Return Date                 | Date when the return was created.            |
| Returned Items              | Number of items to be returned.              |
| State                       | State of the return.                         |

##### Customer section

| ATTRIBUTE          | DESCRIPTION                |
| --------------- | -------------------- |
| Customer reference | Reference of the customer. |
| Name               | Customer name.             |
| Email              | Customer’s email address.  |

##### Main merchant return item states

You can trigger the following states for the returns on the *Overview of Return: [Return Reference]* page:


| RETURN STATE   | DESCRIPTION             |
| ----------------- | ----------------------- |
| waiting for return   | Initial status of the return.                                |
| Execute return               | Select this state when you want to perform the return. When triggering this state, the return status is changed to *returned*. |
| Refund                       | Select this state when you want to refund the returned item. When triggering this state, the return status is changed to *refunded*. |
| Cancel return                | Select this state when you want to cancel the submitted return. When triggering this state, the return status is changed to *return canceled*. |
| Send return back to customer | Select this state when you shipped the returned item back to the customer.  When triggering this state, the return status is changed to *shipped to customer*. |
| Deliver return               | Select this state when the return was delivered to customer. When triggering this state, the return status is changed to *delivered*. |

## Printing a main merchant return slip

For all returns, irrespective of their statuses, you can print the automatically generated [return slip](/docs/marketplace/user/features/{{page.version}}/marketplace-return-management-feature-overview.html#marketplace-return-slip).

To print the return slip, take one of the following steps:

- In the *Actions* column on the *My Returns* page, click **Print slip**.
- On the *Overview of Return: [Return reference]* page, click **Print Return Slip**.

Any of these steps take you to the page with the print version of the return slip.