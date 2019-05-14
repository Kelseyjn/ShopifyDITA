---
gid: fee23dfe-6930-4fcd-9ce7-d972fd10c20e
url: /en/manual/shipping/shopify-shipping/setting-up-shopify-shipping
title: Setting up Shopify Shipping
description: Set up Shopify Shipping to buy shipping labels in your Shopify admin or the Shopify app.
legacy-urls:
  - /manual/apps/apps-by-shopify/canada-post
  - /manual/shipping/labels
weight: 1
keywords:
---

There are a few steps to using shipping labels for your orders:

<div class="grid-container grid-container--halves">
  <div class="grid-item grid-item--fluid__half text-center gutter-bottom">
    <img src="/assets/manual/settings/shipping/shipping_label_1.png" width="200" height="200" alt="">
      <p>Buy a shipping label in your Shopify admin or the Shopify app. You can do this from an order's <b>Fulfillment</b> page.</p>
  </div>
  <div class="grid-item grid-item--fluid__half text-center gutter-bottom">
    <img src="/assets/manual/settings/shipping/shipping_label_2.png" width="200" height="200" alt="">
      <p>Download and print the shipping label. You can use a desktop printer, or a <a href="//help.shopify.com//manual/shipping/shopify-shipping/label-printers">supported label printer</a>.</p>
  </div>
  <div class="grid-item grid-item--fluid__half text-center gutter-bottom">
    <img src="/assets/manual/settings/shipping/shipping_label_3.png" width="200" height="200" alt="">
      <p>Affix it to the outside of your package. If you aren't using labels, then you can use tape or a packing sleeve.</p>
  </div>
  <div class="grid-item grid-item--fluid__half text-center gutter-bottom">
    <img src="/assets/manual/settings/shipping/shipping_label_4.png" width="200" height="200" alt="">
      <p>Drop off your package at any post office.</p>
  </div>
</div>

## Shipping features available by plan

{% include shipping/shipping-features-plans.md %}

## Choose your label printer

Before you can buy shipping labels, you need to [choose the label printer](/manual/shipping/shopify-shipping/label-printers) that you want to use. You can do this on the [**Shipping**](//www.shopify.com/admin/settings/shipping) settings page in your Shopify admin or the Shopify app. For best results, use [Shopify-supported hardware](#shopify-supported-shipping-label-printers) to print your shipping labels.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2.  In the **Shipping labels** section, select the **Label format** that matches the printer you want to use:

    ![Shopify Shipping - printer type](/manual/settings/shipping/printer-type.png)

    Some labels can be printed only by a certain model of printer, so make sure that the type of printer that you choose at this step matches the one that you have:

    <table>
      <tr>
        <th>8.5 × 11 inch paper for desktop printers</th>
        <td>Outputs the label in PDF file format. Choose this if you want to print labels on a desktop printer, or if you want to print two labels per page when you <a href="#buy-and-print-multiple-shipping-labels">buy multiple shipping labels at once</a>.</td>
      </tr>
      <tr>
        <th style="width: 33%;">4 × 6 inch label for label printers</th>
        <td>Outputs the label in PDF file format. Choose this if you want to print labels using a label printer (Dymo, Rollo, or other). </td>
      </tr>
    </table>

After you [set up Shopify Shipping](#overview), you're ready to [buy a shipping label](/manual/shipping/shopify-shipping/buy-and-print) on an order's **Fulfillment** page. You can [print a test shipping label](/manual/shipping/shopify-shipping/buy-and-print/#print-a-test-label) to make sure that your printer is set up properly

> Information:
> Want to use Shopify Shipping for your next fulfillment? You can [buy a shipping label for your most recent order](//www.shopify.com/admin/orders/ship_next?utm_source=docs&utm_medium=docs-callout&utm_campaign=shipping-growth) in your Shopify admin or the Shopify app.

### Shopify-supported shipping label printers

For best results, use [Shopify-supported hardware](/manual/shipping/shopify-shipping/label-printers) to print the shipping labels that you purchase in your Shopify admin or the Shopify app:

<table>
  <tr>
    <th style="width: 33%;"><a href="/manual/shipping/shopify-shipping/label-printers#dymo-labelwriter-4xl">Dymo LabelWriter 4XL</a></th>
    <td>The <strong>Dymo LabelWriter 4XL</strong> is a label printer that connects to your computer via USB. It's available on the <a href="//hardware.shopify.com/products/dymo-4xl-label-printer">Shopify Hardware Store</a>. Recommended for both Mac and Windows computers.</td>
  </tr>
  <tr>
    <th style="width: 33%;"><a href="/manual/shipping/shopify-shipping/label-printers#brother-ql-111onwb-label-printer">Brother QL-1110NWB</a></th>
    <td>It's available on the <a href="//hardware.shopify.com/products/brother-ql-1110nwb">Shopify Hardware Store</a>. Supports USB, wi-fi, and Bluetooth connectivity. Compatible with Mac and Windows computers, and iOS devices.</td>
  </tr>
</table>

If you don't have a label printer, then you can print your shipping labels using a desktop printer instead and affix them to your packages using a plastic sleeve or packing tape.

## Add calculated rates to zones

If you're using Shopify Shipping, then you can [display calculated shipping rates to your customers](/manual/shipping/rates-and-methods/custom-calculated-rates) at checkout. When you have a new business and have limited resources, passing on the exact rate is a simple way to reduce costs.

Calculated shipping using USPS or Canada Post is included by default in your Shopify admin if you're eligible for Shopify Shipping. Shipping costs are calculated automatically by the carrier at the same time an order is placed, so your customers will see real-time rates during checkout.

## Billing schedule

After you buy a shipping label, the cost is billed through your Shopify account.

Shipping bills are charged separately from your Shopify subscription. If you void a shipping label, then its cost will be refunded as a credit towards future label purchases &mdash; it won't be reimbursed directly to your Shopify account.

Your account is charged when you reach a billing threshold that's determined by your current Shopify plan. To learn more about how you're billed for shipping labels, [contact Shopify Support](/questions).

> Note:
> If your store is based in Canada, then you will be billed in USD at the current exchange rate when you buy a shipping label.

## Next steps

* [Buy and print a shipping label in your Shopify admin](/manual/shipping/shopify-shipping/buy-and-print)
* [Review current example shipping rates for Shopify Shipping](/manual/shipping/shopify-shipping/rates)
