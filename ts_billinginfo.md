---

copyright:
  years: 2020
lastupdated: "2020-04-10"

keywords: troubleshoot billing, billing error, billing info, can't access billing, function unavailable

subcollection: billing-usage

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:external: target="_blank" .external}
{:tsSymptoms: .tsSymptoms}
{:tsCauses: .tsCauses}
{:tsResolve: .tsResolve}
{:troubleshoot: data-hd-content-type='troubleshoot'}


# Why can't I access billing information?
{: #cannot-access-billing-info}
{: troubleshoot}

You must have the correct authorization on the account to view billing information. 
{:shortdesc}

When you try to access your billing information, such as payments and invoices, you get a message that says the function isn't available.
{: tsSymptoms}

You see this message because you don't have authorization to view the billing information for the account.
{: tsCauses}

To manage invoices and payments, you need an IAM access policy with the Operator role or higher on the Billing account management service. To view usage information for the entire account, you need the Administrator role on the Billing service. Account owners can always view billing information for the account.

Check your access by completing the following steps:
{: tsResolve}

  1. In the IBM Cloud console, go to **Manage > Access (IAM)**, and select **Users**.
  2. Click your name from the Users page.
  3. Click **Access policies** to view your assigned IAM access policies.
  4. If you don't have the required access, contact the account owner to request it.

For more information about account management services, see [Assigning access to account management services](/docs/iam?topic=iam-account-services).