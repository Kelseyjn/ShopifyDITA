---
url: /en/manual/shipping/shopify-shipping/existing-merchants
gid: f44031a1-a3ef-4856-848d-3a3d927818d7
title: Shopify Shipping
description: Buy and print shipping labels in your Shopify admin to get reduced rates from USPS or Canada Post and save time at the post office.
hidden: true
weight: 3
---

[Shopify Shipping](/manual/shipping/shopify-shipping) provides an out-of-the-box shipping solution for merchants in the United States and Canada. You can display USPS or Canada Post shipping rates to customers at checkout and buy discounted labels directly from your Shopify admin.

{{ 'AJ4bDYnC_Ps' | youtube }}

{% include link-to-more-videos.md %}

## Overview

There are a few steps to using shipping labels for your orders:

<img style="display: block; width: 70%; margin: 0 auto;" src="/assets/images/manual/settings/shipping/shipping-illustration.png" alt="">

1. Buy a shipping label in your Shopify admin. You can do this from an order's **Fulfillment** page.

2. Download and print the shipping label. You can use a desktop printer, or a [supported label printer](/manual/shipping/shopify-shipping/label-printers/).

3. Affix it to the outside of your package. If you aren't using labels, then you can use tape or a packing sleeve.

4. Drop off your package at any post office.

## Plan your shipping strategy

Your shipping strategy will probably change over time as your store grows. One of the first decisions you will need to make is deciding how much to charge for shipping. There are a few different strategies:

  * [free shipping](#free-shipping)
  * [charge exact shipping costs](#charge-exact-shipping-costs)
  * [flat rate shipping](#flat-rate-shipping).

### Free shipping

Offering free shipping will have a positive impact on your cart conversions. There are a few  ways to offer free shipping, even if your business is just getting started. One way is to include the shipping fee in your product prices. Find out what the average cost to ship your product is, then add the buffer into your prices.

Another way is to offer free shipping on all orders over a certain dollar amount. You can set up either [weight or price-based free shipping rates](/manual/shipping/rates-and-methods/free-shipping).

### Charge exact shipping costs

If you are located in the U.S. or Canada, then you can use [Shopify Shipping to display calculated shipping rates](/manual/shipping/shopify-shipping/setting-up-shopify-shipping/#add-calculated-rates-to-zones) to your customers at checkout. If you have a new business and have limited resources, passing on the exact rate is a simple way to reduce costs.

### Flat rate shipping

Another way to charge for shipping is to offer a flat rate for every package, or [flat rates for weight ranges](/manual/shipping/rates-and-methods/manual-rates/#add-weight-based-manual-rates), [destinations](/manual/shipping/zones), or [cart totals](/manual/shipping/rates-and-methods/manual-rates/#add-price-based-manual-rates). When deciding on a flat rate, you will need to consider your average shipping cost to send a package so you don’t over or under charge. An example of a flat rate is to charge $5 for all domestic shipments.

Remember that your goal is to balance your own shipping and handling costs with attractive pricing for your customers. Different shipping strategies might work better at different stages of your business. It’s worth testing out a few different options to see how it impacts your sales.

## Add product weights

Now that you can pull [calculated rates through Shopify Shipping](/manual/shipping/shopify-shipping/setting-up-shopify-shipping/#add-calculated-rates-to-zones), you want to make sure these rates are accurate. Two ways to make sure that you are pulling the most accurate rates possible are:

  * [add product weights](/manual/products/understanding-products)
  * [select packaging](/manual/shipping/understanding-shipping/packaging-and-weights)

Shopify Shipping pulls rates based on the cart weight and box size. Make sure that you have added weights to each of your products and have measured the size of the box you will be shipping. If you use the same box size each time, then [add it as the default package](/manual/shipping/understanding-shipping/initial-setup/#add-a-package-type) for quick rate calculations.


## Add calculated rates to zones

If you're using Shopify Shipping, then you can display calculated shipping rates to your customers at checkout. If you have a new business and have limited resources, passing on the exact rate is a simple way to reduce costs. Calculated shipping using USPS or Canada Post is included by default in your Shopify admin if you're elgible for Shopify Shipping. Shipping costs are calculated automatically by the carrier at the same time an order is placed, so your customers will see real-time rates during checkout.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Zones and rates** section, click **Edit** next to the shipping zone that you want to add calculated rates to: {{ '/manual/settings/shipping/ccs-edit-usps.png' | image }} If you want to add calculated rates to a new zone, then you'll need to [create a new shipping zone](/manual/shipping/zones#create-a-new-shipping-zone) first.

3. In the **Calculated rates** section, click **Add rate**: {{ '/manual/settings/shipping/add-ccs-usps.png' | image }}

4. In the dialog, select the shipping carrier in the **Select a carrier** field.

5. Check the mail classes that you want to offer to your customers in the **Services** section: {{ '/manual/settings/shipping/ccs-mail-class-usps.png' | image }}

6. Check **Automatically offer new shipping services when they become available** in the **Future services** section to include new mail classes by default when they become available.

7. In the **Rate adjustments** section, enter a dollar or percentage value if you want to add a markup to the calculated rate: {{ '/manual/settings/shipping/css-usps-adjustment.png' | image }}

8. Click **Done**.

9. Click **Save** at the top of the shipping zone page: {{ '/manual/settings/shipping/weight-based-manual-save.png' | image }}

## Delete manual rates

You can delete existing manual shipping rates from the [**Shipping**](//www.shopify.com/admin/settings/shipping) page in your Shopify admin.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Zones and rates** section, click **Edit** next to the shipping zone that you want to delete: {{ '/manual/settings/shipping/zone-edit-weight-based.png' | image }}

3. To delete the shipping rate, then click the `x` icon beside it.
  {% block "note" %}
  To suspend a shipping rate without deleting it, set its price or weight range at 0 to 0, and then click **Save**. This preserves most of the rate information so it's easy to reinstate later by correcting the price or weight range.
  {% endblock %}

## Optimize shipping rates

Now that you can pull calculated rates through Shopify Shipping, you want to make sure these rates are accurate. Two ways to ensure you are pulling the most accurate rates possible are:

  * add product weights
  * select packaging

Shopify Shipping pulls rates based on the cart weight and box size. Make sure that you have added weights to each of your products and have measured the size of the box you will be shipping. If you use the same box size each time, then [add it as the default package](/manual/shipping/understanding-shipping/packaging-and-weights) for quick rate calculations.
