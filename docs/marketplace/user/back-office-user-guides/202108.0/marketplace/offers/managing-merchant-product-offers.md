---
title: Managing merchant product offers
last_updated: Apr 19, 2021
description: This topic describes how to view and manage merchant product offers in the Back Office.
template: back-office-user-guide-template
---

This topic describes how to view and manage [merchant product offers](/docs/marketplace/user/features/{{page.version}}/marketplace-product-offer-feature-overview.html) in the Back Office.

## Prerequisites

To start working with offers, go to **Marketplace** > **Offers**.

These instructions assume that there is an existing offer created by the Merchant in the Merchant Portal.

Each section contains reference information. Make sure to review it before you start, or just look up the necessary information as you go through the process.

## Approving or denying offers

Only approved and active offers are available for purchase on the Storefront.

To approve an offer, on the *Offers* page, in the *Actions* column, click **Approve** next to the offer you want to approve.

You can deny the offer by clicking **Deny** on the *Offers* page in the *Actions* column.

**Tips & tricks**

You can sort by offers belonging to a certain Merchant:

![filter-offers-by-merchant](https://spryker.s3.eu-central-1.amazonaws.com/docs/User+Guides/Back+Office+User+Guides/Marketplace/offers/offers/filter-offers-by-merchant.gif)

### Reference information: Approving or denying offers

On the *Offers* page, there is a table with all the offers available in the Marketplace. The table includes:

* Offer ID
* Reference  
* Merchant
* SKU
* Name
* Status
* Visibility
* Stores
* Actions

By default, the table is sorted by the *Offer ID* value.

You can sort the table by other values (*Name* and *Status*) using the sorting icon in the needed column.

![sort-by-other-values](https://spryker.s3.eu-central-1.amazonaws.com/docs/User+Guides/Back+Office+User+Guides/Marketplace/offers/offers-reference-information/back-office-offers.png)

## Viewing an offer

To view an offer, on the *Offers* page, in the *Actions* column, click **View** next to the offer you want to view.

### Reference information: Viewing an offers

The following table describes the attributes on the *View Offer:[Offer Reference]* page:

| SECTION | ATTRIBUTE | DESCRIPTION |
|-|-|-|
| Offer | Reference | Unique identifier of the merchant product offer in the system. |
|  | Status | Current status of the offer. Can be: <ul><li>waiting for approval</li><li>approved</li><li>denied</li></ul>See [Product offer status](/docs/marketplace/user/features/{{page.version}}/marketplace-product-offer-feature-overview.html#product-offer-status) for details on the statuses flow. |
|  | Visibility | Visibility state of the offer. Can be <ul><li>active</li><li>inactive</li></ul>See [Product offer status](/docs/marketplace/user/features/{{page.version}}/marketplace-product-offer-feature-overview.html#product-offer-status) for details on the visibility flow. |
|  | Stores | Stores for which the offer is assigned. |
| Product | SKU | SKU of the product. |
|  | Type | Type of the item. |
|  | Name | Name of the product for every locale. |
|  | Description | Description of the product for every locale. |
| Merchant | Merchant | Name of the merchant who owns the product. |
|  | Merchant SKU | Product SKU of this offer in the Merchant system. |
| Price |   | Table with the default and volume prices defined for the product offer in NET and GROSS mode. |
| Stock   |   | Stock for product offers in every store. |


## Related articles

* [Merchant Product Offer feature overview](/docs/marketplace/user/features/{{page.version}}/marketplace-product-offer-feature-overview.html)
