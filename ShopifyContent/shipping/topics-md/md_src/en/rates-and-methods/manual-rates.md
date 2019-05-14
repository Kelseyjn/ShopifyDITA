---
url: /en/manual/shipping/rates-and-methods/manual-rates
gid: daa908c6-af83-4054-929c-ab876e102f0d
title: Manual shipping rates
short_title: Manual rates
description: You can set your own manual shipping rates if you use regular mail or a fulfillment service to deliver orders from your Shopify store.
weight: 2
keywords:
  - shipping
  - rates
  - charges
  - weights
  - manual
  - flat
  - prices
  - handling
  - single
---

You can set your own manual shipping rates if you use regular mail or a fulfillment service to deliver your orders. You base manual shipping rates on either the [total weight](#add-weight-based-manual-rates) or the [total price](#add-price-based-manual-rates) of the order at checkout.

If a customer chooses one of your manual rates, you'll need to arrange for shipping the order yourself unless you're using a [fulfillment service](/manual/shipping/rates-and-methods/fulfillment-services) or allowing for customer pickup.

## What to charge for shipping

If you don’t know what to charge for shipping, try calling some postal services and asking their advice. They usually have information about delivery costs for various sizes and weights.

Make sure that you add a [handling charge](#add-a-handling-charge) or a surcharge to your shipping rate to make sure that your packaging costs are covered.

>Note:
>A manual shipping rate applies to a [single shipping zone](/manual/shipping/zones). You can't assign a shipping rate to an individual product.

## When to use manual shipping rates

Shipping methods that require manual rates include:

* free delivery
* customer pickup
* various regular postage rates
* deliveries managed by a [fulfillment service](/manual/shipping/rates-and-methods/fulfillment-services).

There are two types of manual shipping rates:

* [Weight-based rates](#add-weight-based-manual-rates) – set your shipping rates based on the total weight of the orders you receive.
* [Price-based rates](#add-price-based-manual-rates) – set your shipping rates based on the price of the orders you receive.

>Tip:
>You don't need to set up manual shipping rates if you're using [calculated-shipping](/manual/shipping/rates-and-methods/custom-calculated-rates).

## Add weight-based manual rates

>Note:
>You must use weight-based rates if you plan to [use a fulfillment service](/manual/shipping/rates-and-methods/fulfillment-services).

{{ 'WLltbe6kJu4' | youtube }}

{% include link-to-more-videos.md %}

You define when a rate applies by setting a condition based on either the weight or total value of an order. The rates that your customers see at checkout reflect the price or weight limits that you've set for each shipping rate.

Weight-based rates are usually more accurate than price-based rates, because they reflect the actual costs of shipping a customer's order. If you use accurate weights for your products in your Shopify admin, then you're less likely to be charged extra for shipping costs by your provider.

Weight-based rates are calculated by adding:

* the combined weight of the products in the order
* the weight of the packaging that you're using.

You can set the weight of your default packaging on the [**Shipping**](//www.shopify.com/admin/settings/shipping) settings page in your Shopify admin.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Zones and rates** section, click **Edit** next to the shipping zone that you want to add the rate to: {{ '/manual/settings/shipping/zone-edit-weight-based.png' | image }} If you want to add a rate to a new zone, then you'll need to [create a new shipping zone](/manual/shipping/zones#create-a-new-shipping-zone) first.

3. Click **Add rate** in the **Weight based rates** section: {{ '/manual/settings/shipping/manual-add-weight-based.png' | image }}

4. In the dialog, enter a descriptive name for the shipping or delivery option in the **Name** field. The name that you enter here appears on the checkout page.

5. In the **Range** section, enter the minimum and maximum weight values for the rate. Your customers are eligible for this shipping rate only if the weight of their order is within the range: {{ '/manual/settings/shipping/weight-based-range.png' | image }}
If you are creating multiple weight-based rates, then make sure that there are [no gaps between your weight ranges](/manual/shipping/rates-and-methods/manual-rates#example-weight-ranges)

6. In the **Rate** section, enter the price of the shipping rate in the **Rate amount field** This amount is added to your customer's order when they select this rate at checkout. Check the **Free shipping rate** checkbox if you want to offer your customers free shipping for this weight class.

> Caution:
> If you create only one weight range and set that range to free shipping, then your customers also receive free shipping for orders with weights outside that range.

7. Click **Done**: {{ '/manual/settings/shipping/add-weight-rate-done.png' | image }}

8. Click **Save** at the bottom of the shipping zone page.

### Example weight ranges

Set up your weight ranges to avoid gaps in applicable rates. After you've entered a weight range, start the next range with a value that has two numbers after the decimal point. For example, the following ranges have no gap:

* **0 kg - 5 kg** = $8
* **5.01 kg - 10 kg** = $14

If you create two weight ranges without decimals, then there is a gap. For example, the following ranges have a gap between 5.01 kg and 5.99 kg:

* **0 kg - 5 kg** = $8
* **6 kg - 14 kg** = $14

If a customer places an order in this weight gap, then Shopify charges the higher shipping rate ($14) by default.

> Caution:
> If you use apps that affect shipping rates and a customer places an order in the gap between two weight ranges, then the customer might not be shown any shipping methods.

## Add price-based manual rates

{{ '29ltgK3oZq8' | youtube }}

{% include link-to-more-videos.md %}

Price-based rates are quick to set up because you don't need to enter individual item weights when you [add products](/manual/products/add-update-products) to your store. However, basing your shipping costs on the total value of an order can be inaccurate, and you might incur additional costs if the items are heavy.

{% block "note-information" %}
All price-based shipping rates are calculated based on discounted totals. If a customer uses a discount code, shipping for the order is calculated based on the discounted order total.
{% endblock %}

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Zones and rates** section, click **Edit** next to the shipping zone that you want to add the rate to: {{ '/manual/settings/shipping/zone-edit-weight-based.png' | image }} If you want to add a rate to a new zone, then you'll need to [create a new shipping zone](/manual/shipping/zones#create-a-new-shipping-zone) first.

3. Click **Add rate** in the **Price based rates** section: {{ '/manual/settings/shipping/manual-add-price-based.png' | image }}

4. In the dialog, enter a descriptive name for the shipping or delivery option in the **Name** field. The name that you enter here appears on the checkout page.

5. In the **Range** section, enter the minimum and maximum order prices for the rate: {{ '/manual/settings/shipping/prices-based-range.png' | image }} Your customers are eligible for this rate only if their order falls between these values.

6. In the **Rate** section, enter the price of the shipping rate in the **Rate amount field**. This amount is added to your customer's order when they select this rate at checkout. Check the **Free shipping rate** checkbox if you want to offer your customers free shipping for this range: {{ '/manual/settings/shipping/price-based-rate-amount.png' | image }}

7. Click **Done**: {{ '/manual/settings/shipping/add-price-rate-done.png' | image }}

8. Click **Save** at the bottom of the shipping zone page.

## Adjust or delete manual shipping rates

You can edit or delete existing shipping rates from the [**Shipping**](//www.shopify.com/admin/settings/shipping) page in your Shopify admin.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Zones and rates** section, click **Edit** next to the shipping zone that you want to edit: {{ '/manual/settings/shipping/zone-edit-weight-based.png' | image }}

3. If you want to edit the shipping rate, then click **Edit**. When you're done making changes, click **Done**.
  {% block "note" %}
  If you change the name of a shipping rate, both the old and the new rates will be preserved. You must [delete a rate](#adjust-or-delete-manual-shipping-rates) to remove it completely.
  {% endblock %}

4. If you want to delete the shipping rate, then click the `x` icon beside it.
  {% block "note" %}
  To suspend a shipping rate without deleting it, set its price or weight range at 0 to 0, and then click **Save**. This preserves most of the rate information so it's easy to reinstate later by correcting the price or weight range.
  {% endblock %}

5. When you're done, click **Save**.

## Add a handling charge

When you're calculating your shipping costs, you should take into account the cost of packaging and the time spent preparing the order for fulfillment. These extra costs are known as handling charges and you can incorporate them in two ways:

* add a fixed amount to your product prices (you can edit these from the [**Products**](https://www.shopify.com/admin/products) page)
* add a fixed amount to your [manual rates](/manual/shipping/rates-and-methods/manual-rates) or a fixed percentage to your [calculated rates](/manual/shipping/rates-and-methods/custom-calculated-rates).

## Add a regional surcharge

Some long-distance delivery regions will inevitably incur greater shipping costs. You might want to protect yourself from potential losses by adding a surcharge to those destinations, while leaving the rates for the rest of the destination country unchanged.

#### Steps:

1. [Create a new shipping zone](/manual/shipping/zones#create-a-new-shipping-zone) for the region that requires a surcharge.

2. [Create a new shipping rate](#when-to-use-manual-shipping-rates) for that zone. Make sure that you enter pricing information for the rate that includes the necessary surcharge amount.


## Create a custom shipping rate for a single order

If you want to set a custom shipping rate for an individual order, you can do so by [manually creating a new order](/manual/orders/create-orders) in your Shopify admin.
