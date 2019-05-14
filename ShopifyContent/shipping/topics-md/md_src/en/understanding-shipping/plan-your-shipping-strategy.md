---
gid: 6075cdfa-4b02-40e7-b434-aea1d0f21da9
url: /en/manual/shipping/understanding-shipping/plan-your-shipping-strategy
title: Plan your shipping strategy
description: Learn more about how to build your store's shipping strategy.
legacy-urls:
  - manual/shipping/customer-experience
  - /manual/shipping/understanding
  - /manual/shipping/customer-experience
weight: 1
keywords:
  - free shipping
  - flat rate
  - shipping rates

---

Setting up your shipping rate is an important part of setting up your business. Before you take your first order, you need to decide what shipping strategy you want to use, and then set up how your customers can choose a shipping method.

## Shipping strategies

Your shipping strategy will probably change over time as your store grows. One of the first decisions you will need to make is deciding how much to charge for shipping.

> Note:
> If you manage your inventory across [multiple locations](/manual/locations), then you need to offer flat shipping rates or the same shipping rates from all your locations.

### Free shipping

Offering free shipping will have a positive impact on your cart conversions. There are a few  ways to offer free shipping, even if your business is just getting started. One way is to include the shipping fee in your product prices. Find out what the average cost to ship your product is, then add the buffer into your prices.

Another way is to offer free shipping on all orders over a certain dollar amount. You can set up either [weight or price based free shipping rates](/manual/shipping/rates-and-methods/free-shipping).

### Charge exact shipping costs

If you are located in the U.S. or Canada, then you can use [Shopify Shipping to display calculated shipping rates](/manual/shipping/shopify-shipping/setting-up-shopify-shipping/#add-calculated-rates-to-zones) to your customers at checkout. If you have a new business and have limited resources, passing on the exact rate is a simple way to reduce costs.

### Flat rate shipping

Another way to charge for shipping is to offer a flat rate for every package, or [flat rates for weight ranges](/manual/shipping/rates-and-methods/manual-rates/#add-weight-based-manual-rates), [destinations](/manual/shipping/zones), or [cart totals](/manual/shipping/rates-and-methods/manual-rates/#add-price-based-manual-rates). When deciding on a flat rate, you will need to consider your average shipping cost to send a package so you don’t over or under charge. An example of a flat rate is to charge $5 for all domestic shipments.

Remember that your goal is to balance your own shipping and handling costs with attractive pricing for your customers. Different shipping strategies might work better at different stages of your business. It’s worth testing out a few different options to see how it impacts your sales.

## Optimize shipping rates

Now that you can pull [calculated rates through Shopify Shipping](/manual/shipping/shopify-shipping/setting-up-shopify-shipping#add-calculated-rates-to-zones), you want to make sure these rates are accurate. Two ways to make sure that you are pulling the most accurate rates possible are:

  * [add product weights](/manual/products/understanding-products)
  * [select packaging](/manual/shipping/understanding-shipping/packaging-and-weights)

Shopify Shipping pulls rates based on the cart weight and box size. Make sure that you have added weights to each of your products and have measured the size of the box you will be shipping. If you use the same box size each time, then [add it as the default package](/manual/shipping/understanding-shipping/initial-setup/#add-a-package-type) for quick rate calculations.

## Set up shipping in Shopify

#### Steps:

1. [Enter your shipping origin](/manual/shipping/understanding-shipping/initial-setup/#add-a-shipping-origin-address).
2. [Add shipping zones](/manual/shipping/zones).
3. [Add shipping rates or activate calculated shipping](/manual/shipping/rates-and-methods) for zones.
4. If you're using Shopify Shipping to buy and print shipping labels, [choose your label printer and default packaging types](/manual/shipping/shopify-shipping/buy-and-print).

## Fulfill orders

The process of shipping your products to your customers is referred to in Shopify as [order fulfillment](/manual/orders). You can view and fulfill your orders, and create new orders manually, from the [**Orders**](//www.shopify.com/admin/orders) page in your Shopify admin.

You can fulfill your orders in a few different ways:

* [fulfill orders manually](/manual/orders/fulfill-orders)
* [use carriers](/manual/shipping/rates-and-methods/custom-calculated-rates) who calculate shipping prices for you
* [use a fulfillment service](/manual/shipping/rates-and-methods/fulfillment-services) to ship your orders for you.

## Customer experience

The shipping settings that you use affect what your customers see at checkout.

After you've set up your shipping rates, you can place a test order using your own checkout to see what options your customers have and make sure that your rates are appearing correctly.

### How your customers choose a shipping method

As soon as your customers reach checkout and enter a shipping address, their shipping methods are displayed. Although you can configure many options in your store's shipping settings, each customer is shown only those applicable to their order. The most inexpensive option is shown as the default:

{{ '/manual/shipping/shipping-checkout-options.png' | image }}

{% block "note-reminder" %}
Your customers won't see their shipping methods until they enter a delivery address.
{% endblock %}

If your customer leaves the checkout page to change the contents of their order, then their shipping rates might change. Since most shipping rates are calculated based on an order's weight, any significant changes to its contents can make the original shipping rate inaccurate. When your customer returns to the checkout process after changing their order, they're redirected back to the same step of the checkout process. They won't receive the new, recalculated shipping rate until they're ready to complete their purchase.

Customers who enter a shipping address in a region that isn't included in your shipping zones receive a notice that there is no shipping rate available for their region:

{{ '/manual/shipping/no-rate-available.png' | image }}

### Checking out with PayPal Express

If your customers are checking out by using PayPal Express, they are first taken to the PayPal page to enter their credit card information and billing address. After this step, they’re shown available shipping methods.

You might want to inform your customers that they will encounter this intermediate step if they’re using PayPal Express. An easy way to do this is to [create an information page](/manual/sell-online/online-store/pages) and [link it](/manual/sell-online/online-store/menus-and-links) to the footer of your store.
