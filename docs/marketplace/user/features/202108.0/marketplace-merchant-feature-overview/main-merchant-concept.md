---
title: Main merchant concept
description: This document contains concept information for the main merchant in the Spryker Commerce OS.
template: concept-topic-template
---

The Spryker Marketplace platform offers sales opportunities to everyone. To help support the [Enterprise Marketplace](/docs/marketplace/user/intro-to-the-spryker-marketplace/marketplace-concept.html) model, not only the 3rd party merchants but also the company-owner of the Marketplace store can sell their products and offers online. We call this company the **main merchant**.

Thus, the main merchant acts as a common [marketplace merchant](/docs/marketplace/user/features/{{page.version}}/marketplace-merchant-feature-overview/marketplace-merchant-feature-overview.html) having all its characteristics.

## Main merchant orders and returns

Being both the [Marketplace Operator](/docs/marketplace/user/intro-to-the-spryker-marketplace/marketplace-personas.html) and the seller, and already performing tasks in the Back Office, the main merchant manages their [merchant orders](/docs/marketplace/user/features/{{page.version}}/marketplace-order-management-feature-overview/merchant-order-overview.html) also in the Back Office. See [Managing main merchant orders](/docs/marketplace/user/merchant-portal-user-guides/{{page.version}}/orders/managing-merchant-orders.html) for details.

## Main merchant state machine

To manage merchant orders of the main merchant, the *Main merchant state machine* exists. Out of the box, the main merchant state machine provides the following states:

- created

- new

- canceled

- left the merchant location

- arrived at the distribution center

- shipped

- delivered

- closed



The workflow of the Main merchant state machine is schematically displayed in the diagram below:

![img](https://spryker.s3.eu-central-1.amazonaws.com/docs/Marketplace/user+guides/Features/Marketplace+Merchant/Main+merchant+concept/main-merchant-state-machine-new.png)

## Main merchant returns

If the [Marketplace Return Management](/docs/marketplace/user/features/{{page.version}}/marketplace-return-management-feature-overview.html) feature is integrated into the project, the main merchant state machine obtains an additional return subprocess and the flow looks like this:

![img](https://spryker.s3.eu-central-1.amazonaws.com/docs/Marketplace/user+guides/Features/Marketplace+Merchant/Main+merchant+concept/marketplace-main-merchant-return-process.png)
