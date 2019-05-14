---
url: /en/manual/shipping/rates-and-methods/fulfillment-services/amazon
gid: b73de6ea-14aa-4169-9e07-f5dd911e4776
title: Fulfillment by Amazon
description: Fulfillment by Amazon lets you store your inventory and fulfill your orders from an Amazon.com fulfillment center.

weight: 3

keywords:
  - fulfillment
  - Amazon
  - inventory
  - dropshipping
  - rates
  - FBA

queries:
- fba
---

You can use Fulfillment by Amazon to store your inventory at and fulfill your orders from an Amazon.com fulfillment center. Before you set this up, you'll need to have an Amazon Seller Central account.

If you use Fulfillment by Amazon for a product, then you can't also stock the product in the  [locations](/manual/locations/) that you manage.

> Note:
> When you cancel an order in Shopify that includes a product fulfilled by Amazon, you need to manually cancel the fulfillment in Amazon as well to prevent the product from being shipped.

## Activate Fulfillment by Amazon

> Note:
>Shopify's built-in Fulfillment by Amazon integration is available only for stores in the United States (excluding APO and FPO addresses) and Canada. For stores outside of the United States or Canada, fulfillment by Amazon requires [third-party app integration](//apps.shopify.com/search/query?utf8=%E2%9C%93&q=amazon+fba).

{% comment %}
Canadian and American shops using CAD or USD have FBA integration available. If you’re selling in any other currency, then the only other option is to use US FBA integration. In-built FBA integration is not available for any international store other than US or Canada.
{% endcomment %}

#### Steps:

1. After you've set up your Amazon Seller Central account, go to [https://www.shopify.com/admin/fulfillment_services/signup_for_mws](https://www.shopify.com/admin/fulfillment_services/signup_for_mws).
2. On the **Amazon Marketplace Web Service (Amazon MWS)** page, follow the instructions to link your Shopify store with your Fulfillment by Amazon account.
3. Click continue to complete the process and return to your Shopify Store.

After you've activated Fulfillment by Amazon, you should [add Amazon's shipping rates](#set-shipping-rates-for-fulfillment-by-amazon) to your own shipping settings.

## Set shipping rates for Fulfillment by Amazon

After you've [activated Fulfillment by Amazon](#activating-fulfillment-by-amazon), you need to create new Amazon shipping rates in your Shopify admin. These appear to your customers at checkout.

Amazon offers the following shipping rates:

* Standard Shipping
* Expedited Shipping
* Priority Shipping

For each of your shipping zones, you need to [add separate shipping rates](/manual/shipping/rates-and-methods) that match each of these Amazon shipping rates.

When setting your shipping rates, you might want to take a look at <a href="http://www.amazon.com/gp/help/customer/display.html/?nodeId=201119430">Amazon's fulfillment rates</a> to help you decide what to charge.

Make sure that you complete the following tasks:

* Create a separate rate for each Amazon shipping option.
* Copy the name of the Amazon shipping rates (either Standard Shipping, Expedited Shipping, or Priority Shipping) into the **Shipping rate name** field.
* [Set the **Criteria** to **Based on order weight**](/manual/shipping/rates-and-methods/manual-rates#add-weight-based-manual-rates), not price.

If your shipping rates are set up incorrectly, then you might get an error while fulfilling an order through Amazon. If you notice this error, return to your shipping rates, and make sure they match the criteria listed above.

If you want to markup your shipping rates to cover Amazon's fulfillment fees, then you can add weight and price information to reflect Amazon's [Fulfillment Fees for Multi-Channel Fulfillment Orders](//www.amazon.com/gp/help/customer/display.html/?nodeId=201119430).

## Configure products for Fulfillment by Amazon

> Note:
> Make sure you've [activated Fulfillment by Amazon](#activating-fulfillment-by-amazon) and [added their shipping rates](#set-shipping-rates-for-fulfillment-by-amazon) before you configure your products.

The procedure for configuring your products varies slightly depending on whether you are:

* [Configuring new products for Fulfillment by Amazon](#configuring-new-products-for-fulfillment-by-amazon)
* [Configuring existing products for Fulfillment by Amazon](#configuring-existing-products-for-fulfillment-by-amazon)

### Configure new products for Fulfillment by Amazon

#### Steps:

1. When you’re [adding a new product](/manual/products/add-update-products), scroll down to the **Shipping** section of the [**Add a product**](//www.shopify.com/admin/products/new) page.
2. Select **Amazon Marketplace Web** from the **Fulfillment service** drop-down menu.
3. In the **Inventory** section, select **Amazon Marketplace Web tracks this variant's inventory** from the **Inventory policy** drop-down menu.
  > Note:
  > You can set your inventory to be tracked by Shopify, but it is recommended you select Amazon to make sure that you maintain correct inventory levels for your fulfillment and dropshipping service.

4. Make sure that you've entered exact values in the **Weight** and **SKU** fields. These must match the values you used for your Fulfillment by Amazon product list. In Amazon the SKU is called **Seller SKU** or **Merchant SKU** (**MSKU**).
5. When you're done, click **Save product**.

### Configure existing products for Fulfillment by Amazon

#### Steps:

{% include admin_sidebar/products.md %}

2. Click the name of the product you want to enable fulfillment for.
3. In the **Shipping** section, select **Amazon Marketplace Web** from the **Fulfillment service** drop-down menu.
4. In the **Inventory** section, select **Amazon Marketplace Web tracks this variant's inventory** from the **Inventory policy** drop-down menu.
5. Make sure that you've entered correct values in the **Weight** and **SKU** fields. These must match the values you used for your Fulfillment by Amazon product list.  In Amazon the SKU is called **Seller SKU** or **Merchant SKU** (**MSKU**).
6. When you're done, click **Save**.

> Tip:
> If you have many products to edit, then you might want to [use the bulk editor](/manual/productivity-tools/bulk-editing-products) or [export your products as a .csv file](/manual/products/import-export/export-products).

## Fulfill orders with Fulfillment by Amazon

After your products are configured, Amazon automatically syncs with your orders every hour. You can manually sync orders with Amazon to fulfill them from a fulfillment center.

#### Steps:

{% include admin_sidebar/orders.md %}

2.  From the **Orders** page, click the order number.

3.  In the **Order Details** section, click **Start fulfilling** to open the order’s **Fulfillment** page.
    By default, every line item is set to be fulfilled, but you can [fulfill part of an order](/manual/orders/fulfill-orders#fulfill-part-of-an-order-manually) if you want.

4.  Select **Mark as fulfilled**.

5.  Click **Fulfill items** to mark the order as **Fulfilled**.

> Note:
> When you cancel an order in Shopify that includes a product fulfilled by Amazon, you need to manually cancel the fulfillment in Amazon as well to prevent the product from being shipped.

### View the order status

After you mark an order as fulfilled in Shopify, you need to wait for Amazon to accept or reject the order. You can view an order's status from the **Orders** page.

#### Steps:

{% include admin_sidebar/orders.md %}

2. View the order's fulfillment status in the **Fulfillment status** column:
  - If the order hasn't synced with Amazon yet, then it has an `Open` status.
  - If the order was accepted by Amazon, then it has a `Fulfilled` status.
  - If the order was rejected by Amazon because of an error, then it has an `Unfulfilled` status.


After you mark an order as fulfilled, you can review the order's fulfillment details from the **Timeline** section on the order's page.

## Deactivate Fulfillment by Amazon

#### Steps:

1. From your Shopify admin, go to **Settings** > **Shipping**.
2. In the **FulFillment by Amazon** section, click **Deactivate**.
