---
gid: a545cc70-8272-4daa-95c1-1f5be4b5e745
url: /en/manual/shipping/rates-and-methods/custom-calculated-rates/setup-custom-calculated-rate
title: Set up custom calculated rates
short_title: Set up custom calculated rates
description: Setting up a custom calculated rate with your shipping carrier account.
weight: 1
keywords:
  - calculated
  - real time
  - carrier calculated
  - carrier-calculated
  - carriers
  - rates
  - third-party
  - third party
  - own account
  - custom account
---

Although shipping carriers offer a wide range of rates, your customers are only presented with the rates that are applicable to their order. Whether or not a shipping rate is applicable depends on the following factors:

* the total weight of the order
* your [default shipment dimensions](/manual/shipping/rates-and-methods/custom-calculated-rates/default-shipment-dimensions). These are used by your carrier to calculate shipping rates
* whether they enter their **Company** name at checkout (this can make them eligible for business rates, which are generally lower than residential rates).

If you plan to offer calculated shipping for your products, then make sure that you've entered accurate weights for each variant, either in your [product detail pages](/manual/products/understanding-products) or your [product CSV file](/manual/products/import-export/#product-csv-file-format). If your weights are not accurate, then the calculated shipping costs will be incorrect.

> Caution:
> If you change plans from a Basic Shopify monthly or Shopify monthly to an annual plan and you're using calculated shipping on the monthly plan, then your shipping carrier information resets because you're starting a new contract with Shopify. In this case, you need to reenter account information for each carrier.

## Which carriers to use

When you first set up your Shopify store, you can choose from available carriers on your [**Shipping**](//www.shopify.com/admin/settings/shipping) settings page:

* [USPS](/manual/shipping/rates-and-methods/custom-calculated-rates/usps)
* [Canada Post](/manual/shipping/rates-and-methods/custom-calculated-rates/canada-post)
* [FedEx](/manual/shipping/rates-and-methods/custom-calculated-rates/fedex)
* [UPS](/manual/shipping/rates-and-methods/custom-calculated-rates/ups)

You can [add other carriers by installing their apps](https://apps.shopify.com/search/query?utf8=%E2%9C%93&q=shipping) from the Shopify App Store.

## Basic procedure for offering calculated shipping

The basic procedure for offering a calculated rate for calculated shipping looks like this:

1. Register for and set up an account with your preferred carrier.
2. Get your carrier account credentials.
3. Activate the carrier service in Shopify.
4. Make sure your [shipping origin](/manual/shipping/understanding-shipping/initial-setup) address is correct.
5. Make sure your products have accurate weights.
6. [Add rates for this carrier to each of your applicable shipping zones](/manual/shipping/zones).

## Add a calculated shipping rate

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Shipping rates at checkout** section, find the shipping zone that you want to create the new rate for, and then click **Edit**: {{ '/manual/settings/shipping/add-shipping-rate-carrier.png' | image }}

3. In the **Calculated rates** section, click **Add rate**: {{ '/manual/settings/shipping/add-cc-rate.png' | image }}

4. On the **Add calculated rate** dialog, select the carrier from the drop-down menu and check the services that you want to offer to your customers:

    {{ '/manual/settings/shipping/set-up-cc-rate.png' | image }}

    > Note:
    > If you select **Automatically offer new shipping services when they become available**, then new, unlisted rates can appear in the checkout.


5. If you want to add a handling charge on top of the calculated rate, then enter an amount in either the **Percentage** or **Flat fee** field.

6. When you're done, click **Done**.

7. On the shipping zone's main page, click **Save** to save the calculated rate.

## Adjusting calculated rates

You can adjust calculated shipping rates to mark up or discount the rates that your customers see at checkout. You might want to adjust calculated shipping rates if:

* the rate is too high to attract customers
* the rate is too low to cover your packaging and handling costs.

You can mark up calculated shipping rates by an additional flat fee or by a percentage of the total shipping rate. If you adjust a calculated shipping rate to include both an additional flat fee and a percentage markup, then the percentage is calculated before the flat fee is added. For example, a $5.00 rate with 50% markup and a $1.00 flat fee will cost the customer $8.50, not $9.00.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Shipping rates at checkout** section, click **Edit** next to the shipping zone that you want to edit: {{ '/manual/settings/shipping/zone-edit-weight-based.png' | image }}

3. In the **Calculated rates** section, click **Edit** beside the rate you want to adjust: {{ '/manual/settings/shipping/edit-cc-rate.png' | image }}

4. Adjust each rate by entering a fixed amount in the **Flat fee** field, or a percentage in the **Percentage** field: {{ '/manual/settings/shipping/adjust-shipping-cost.png' | image }} If you want to offer your customers a discounted rate, then enter a negative percentage in the **Percentage** field. Since you will still be charged the full shipping cost that's calculated by the carrier, you might want to recover some of that cost by adding an equivalent amount to your product prices.
  {% block "note" %}
  If you add a percentage markup and a flat fee to a calculated rate, then the percentage markup is calculated before the flat fee is added.
  {% endblock %}

5. Click **Done**.

6. On the shipping zone's main page, click **Save**.

>Note:
>Your [default shipment dimensions](/manual/shipping/rates-and-methods/custom-calculated-rates/default-shipment-dimensions/) will also be used by your carrier to calculate shipping rates.


## Deactivate a shipping carrier service

If you no longer want to use a particular carrier service (for example if your account with them has expired), then you need to make sure the service isn't offered to your customers at checkout.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Carrier accounts** section, click **Manage carriers**.

3. Click **Disconnect account** next to the carrier that you want to remove.

4. In the dialog, click **Disconnect account** to confirm the deactivation.

>Note:
>If your account with the carrier is in good standing, then you can reactivate the carrier at any time.
