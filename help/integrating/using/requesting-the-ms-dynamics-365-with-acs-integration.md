---
solution: Campaign Standard
product: campaign
title: Request and configure the Microsoft Dynamics 365 integration
description: Learn how to Request and configure the Microsoft Dynamics 365 with Campaign Standard integration
audience: integrating
content-type: reference
topic-tags: working-with-campaign-and-ms-dynamics

---

# Request and configure the Microsoft Dynamics 365 integration

In order to provision this integration, you will need to follow the steps below.

Please follow the flowchart and flowchart details below to request and configure the integration.

![](assets/provisioning-wf.png)

Flowchart Details (maps to steps above):

* **Step 1** - It is assumed that you already have, or are in the process of procuring, a license for Microsoft Dynamics 365 for Sales and for Adobe Campaign Standard.

* **Step 2** - The standard integration offering is free to all customers; however, additional costs may apply depending on your requirements (see [Integration guardrails and boundaries](../../integrating/using/ms-dynamics-365-integration-guardrails.md). A new sales order will need to be signed in order to take advantage of the integration.

* **Step 3** - Complete pre-integration steps for Dynamics 365 and Campaign. See [Configure this integration](#configure-this-integration).

* **Steps 4-7** - The Adobe onboarding team will work with you through the onboarding process.

## Configure this integration {#configure-this-integration}

Three systems need to be provisioned and configured for this integration: Adobe Campaign Standard, Microsoft Dynamics 365 for Sales and the integration tool. Configuration articles are linked below.

>[!CAUTION]
>
>For each system, these steps need to be performed by an administrator.
>
>Steps in the articles below will guide you through creating integrations/registrations that involve assigning permissions and/or admin access.  It is your responsibility to ensure these steps comply with your company policies before performing, and to perform them carefully.

In ADOBE CAMPAIGN, you need to set up API access and configure a new integration for the integration tool. To achieve this, refer to [this article](../../integrating/using/configure-adobe-io-for-ms-dynamic.md).

In MICROSOFT DYNAMICS 365, you need to create a new app registration and enable an application user to use the integration.  To configure Microsoft Dynamics 365 for this integration, refer to [this article](../../integrating/using/configure-microsoft-dynamics-365-for-campaign-integration.md).

You will need to work with the Adobe onboarding team to set up the configuration for ingress, egress, and opt-out data flows.


## Request support 

Support tickets can be logged with Adobe Custom Care, as usual; Customer Care will bring in support personnel, as needed.

For any issues with integration data flows, make sure to include the report suite as part of the issue description as well as the following information:

* **Process Owner**: Engineering Architects

* **ES Process ID**: Provided during onboarding process

* **Process Title**: Dynamics 365 / Adobe Campaign Standard Integration

* **Issue Description**: Description of the issue

Integration support coverage is currently 24x5 (available Monday through Friday, excluding Adobe holidays and break periods).