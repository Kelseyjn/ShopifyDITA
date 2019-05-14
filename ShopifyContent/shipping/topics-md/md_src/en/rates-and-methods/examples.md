---
url: /en/manual/shipping/rates-and-methods/examples
gid: 81349c97-9355-4e03-8abd-a897f52d91e0
title: Examples of shipping rates
short_title: Examples
description: Some examples of shipping settings and special shipping scenarios for your online Shopify store.
img: icon-truck
weight: 7
keywords:
    - flat rates
    - rates
    - examples
    - zones
---

You'll probably want to define some different shipping rates for your store, depending on how many choices you want to offer to your customers. You can also offer [free shipping](/manual/shipping/rates-and-methods/free-shipping) to promote your products.

## Tiered shipping rates

If you want to set a series of tiered shipping rates, then the weights or price ranges that you set must not overlap. For example, to set a $10 rate to Canada for orders up to 25 kg, and a $15 rate for orders of 25-50 kg:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Shipping zones** section, click **Edit** next to the shipping zone that you want to add the rate to. If you want to add the rate to a new zone, then you'll need to [create a new shipping zone](/manual/shipping/zones#create-a-new-shipping-zone) first.

3. Click **Add rate** in the **Weight based rates** section: {{ '/manual/settings/shipping/manual-add-weight-based.png' | image }}

4. [Create a new weight-based shipping rate](/manual/shipping/rates-and-methods/manual-rates/#add-weight-based-manual-rates) that sets the upper limit of the first tier to `25 kg`: {{ '/manual/settings/shipping/tiered-shipping-low-range.png' | image }}

5. Create a second weight-based shipping rate that sets the range of the second tier to 25.01-50 kg: {{ '/manual/settings/shipping/tiered-shipping-high-range.png' | image }}

8. Click **Save** at the bottom of the shipping zone page.

## Shipping rates based on quantity purchased

It's possible to offer a quantity-based shipping rate in Shopify if you sell a range of items with identical weights or prices. This is useful if, for example, you want to offer a shipping discount based on the number of items purchased.

> Note:
> Make sure you apply this rate only to products with identical [weights](/manual/shipping/rates-and-methods/manual-rates#add-weight-based-manual-rates) or [prices](/manual/shipping/rates-and-methods/manual-rates#add-price-based-manual-rates).

For example, you might sell T-shirts weighing 0.5 kg, and charge $2 each for shipping. This means that 3 T-shirts, for example, would usually cost the customer $6 in delivery charges. You could offer a shipping discount for orders of 3 or more T-shirts by setting a shipping rate of $4 for orders weighing 1.5 kg, up to some imaginary maximum.
￼
{{ '/manual/settings/shipping/ship-by-quantity.png' | image }}
