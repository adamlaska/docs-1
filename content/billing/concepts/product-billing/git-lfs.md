---
title: Git Large File Storage billing
intro: 'Learn about billing for {% data variables.large_files.product_name_long %} using the new billing platform.'
versions:
  feature: enhanced-billing-platform
redirect_from:
  - /github/setting-up-and-managing-billing-and-payments-on-github/about-billing-for-git-large-file-storage
  - /articles/about-billing-for-git-large-file-storage
  - /github/setting-up-and-managing-billing-and-payments-on-github/managing-billing-for-git-large-file-storage/about-billing-for-git-large-file-storage
  - /billing/managing-billing-for-git-large-file-storage/about-billing-for-git-large-file-storage
  - /billing/using-the-enhanced-billing-platform-for-enterprises/about-enhanced-billing-for-git-large-file-storage
  - /billing/using-the-new-billing-platform/about-git-large-file-storage
  - /billing/using-the-new-billing-platform/about-billing-for-git-large-file-storage
  - /billing/managing-billing-for-your-products/managing-billing-for-git-large-file-storage/about-billing-for-git-large-file-storage
topics:
  - Billing
  - LFS
  - Enterprise
  - Team
  - Upgrades
shortTitle: Git LFS
product: '{% data reusables.billing.enhanced-billing-platform-product %}'
contentType: concepts
---

## About billing for {% data variables.large_files.product_name_long %}

> [!NOTE] {% data reusables.user-settings.context_switcher %}

Each {% data variables.product.prodname_dotcom %} account receives a certain amount of free bandwidth and storage for {% data variables.large_files.product_name_short %}, depending on the account's plan.
Bandwidth is billed for each GiB of data downloaded. Storage is billed by calculating an hourly usage rate. To estimate costs for paid {% data variables.large_files.product_name_short %} usage, you can use the {% data variables.product.prodname_dotcom %} [pricing calculator](https://github.com/pricing/calculator?feature=lfs).

{% data reusables.large_files.owner_quota_only %}

## Included bandwidth and storage (per month)

The following amounts of bandwidth and storage are included for free with your {% data variables.product.company_short %} account.

|Plan | Bandwidth | Storage |
|------- | ------- | ---------|
| {% data variables.product.prodname_free_user %} | {% data variables.large_files.included_bandwidth_free_pro %} | {% data variables.large_files.included_storage_free_pro %} |
| {% data variables.product.prodname_pro %} | {% data variables.large_files.included_bandwidth_free_pro %} | {% data variables.large_files.included_storage_free_pro %} |
| {% data variables.product.prodname_free_team %} for organizations | {% data variables.large_files.included_bandwidth_free_pro %} | {% data variables.large_files.included_storage_free_pro %} |
| {% data variables.product.prodname_team %} | {% data variables.large_files.included_bandwidth_team_enterprise %} | {% data variables.large_files.included_storage_team_enterprise %} |
| {% data variables.product.prodname_ghe_cloud %} | {% data variables.large_files.included_bandwidth_team_enterprise %} | {% data variables.large_files.included_storage_team_enterprise %} |

## Pricing for paid usage

If you use more than the included amount of bandwidth or storage for your plan throughout the month, you can still use {% data variables.large_files.product_name_short %}. {% data variables.product.company_short %} bills for additional GiBs of data at the rates below.

| Product   | Price per-GiB (USD) |
| --------- | ------------------- |
| Bandwidth | $0.0875 |
| Storage   | $0.07   |

To view your current storage and bandwidth, see [AUTOTITLE](/billing/managing-billing-for-your-products/viewing-your-product-usage).

### Sample storage cost calculation

For example, if you use 1 GiB above what is included for free for the first 15 days of April, then use 2 GiB starting from April 16th to the end of the month, your storage costs will be calculated in the following way.

* 1 GiB × 15 days × 24 hours per day = 360 GiB-hours
* 2 GiB × 15 days × 24 hours per day = 720 GiB-hours
* 360 GiB-hours + 720 GiB-hours = 1080 GiB-hours
* 1080 GiB-hours / 720 hours in the month = 1.5 GiB-months

In this example, {% data variables.product.company_short %} would bill for 1.5 GiB of storage for the month of April.

## Managing your budget for {% data variables.large_files.product_name_long %}

{% data reusables.billing.default-over-quota-behavior %}

## Further reading

* [AUTOTITLE](/repositories/working-with-files/managing-large-files/about-git-large-file-storage)
* [AUTOTITLE](/repositories/working-with-files/managing-large-files/installing-git-large-file-storage)
* [AUTOTITLE](/repositories/working-with-files/managing-large-files/about-storage-and-bandwidth-usage)
