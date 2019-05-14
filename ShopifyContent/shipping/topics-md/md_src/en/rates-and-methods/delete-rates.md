---
url: /en/manual/shipping/rates-and-methods/delete-rates
gid: 72fd87b1-a8ba-4a9f-9962-58a14b5a4c93
title: Suspend or delete a shipping rate
short_title: Suspend or delete rates
description: You can temporarily withdraw a shipping rate for a destination or delete it completely from your online Shopify store.
legacy-urls:
- /manual/shipping/rates-and-methods/suspend-delete-shipping-rates
weight: 4
keywords:
- shipping
- rates
- zones
---

## Suspend a shipping rate

If you want to hide a shipping rate from your customers but still keep it in your Shopify admin, then you can suspend the rate temporarily. This preserves most of the rate information so that you can reinstate the shipping rate later by correcting the weight or price range. You might want to suspend a shipping rate if you're pausing a promotional shipping rate that you want to use again in the future or if you're testing changes to your shipping strategy.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Shipping zones** section, click **Edit** next to the shipping zone that contains the shipping rate that you want to suspend: {{ '/manual/settings/shipping/edit-zone-based-rate.png' | image }}

3. On the shipping zone's page, find the shipping rate that you want to suspend, and then click **Edit**.

4. Set the price or weight range at `0` to `0`, and then click **Done**.
For example, if you want to suspend a weight-based shipping rate, then you need to enter `0` in the **Minimum order weight** and **Maximum order weight** fields: {{ '/manual/settings/shipping/suspend-weight-based-rate.png' | image }}

5. Click **Done**.

6. On the shipping zone's main page, click **Save**.

## Delete a shipping rate

If you want to stop offering a shipping rate to your customers, then you can delete it. You might want to delete a shipping rate if a shipping discount that you've been offering has come to an end, or if a particular delivery mechanism is no longer cost-effective.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Shipping rates** section, click **Edit** next to the shipping zone that contains the shipping rate that you want to delete: {{ '/manual/settings/shipping/edit-zone-based-rate.png' | image }}

3. On the shipping zone's page click the `x` icon next to the shipping rate that you want to delete: {{ '/manual/settings/shipping/delete-shipping-rate.png' | image }}

4. Click **Save**.

## Delete all the shipping rates for a region or country

To delete all the rates for a particular region, you can do one of the following:

* Delete each rate [individually](#delete-a-shipping-rate).
* Delete the region. This removes all rates associated with that region or zone.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Shipping rates** section, click **Edit** next to the shipping zone that you want to delete: {{ '/manual/settings/shipping/edit-zone-based-rate.png' | image }}

3. At the bottom of the shipping one's page, click **Delete zone**.

4. In the dialog, click **Delete shipping zone** to confirm: {{ '/manual/settings/shipping/delete-zone-confirm.png' | image }}
