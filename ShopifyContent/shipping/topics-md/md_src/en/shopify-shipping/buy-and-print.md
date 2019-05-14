---
url: /en/manual/shipping/shopify-shipping/buy-and-print
gid: 3d8b2971-607a-4d21-8934-b6dde6e1c88a
title: Buy and print shipping labels
short_title: Buy and print shipping labels
description: Buy and print shipping labels in your Shopify admin or the Shopify app
legacy-urls:
  - /manual/shipping/labels/buy-and-print
weight: 3
keywords:
  - printing
  - labels
  - shipping
  - voiding
  - buying
  - testing
  - canceling
  - cancelling
  - voiding
  - void
  - customs
  - forms
---

Shopify Shipping is available for orders shipped from fulfillment locations in the United States (USPS, DHL Express, and UPS) and Canada (Canada Post). UPS doesn't support P.O. box addresses. You need to update your address to a street address to create and send shipping labels. If your fulfillment locations aren't based in the US or Canada, then use a [shipping label app](https://apps.shopify.com/search?q=shipping+label) instead.

If you use Shopify Shipping, then you can buy shipping labels when you're [fulfilling an order](/manual/orders/fulfill-orders/) in your Shopify admin or the Shopify app. After you buy a label, you can [print](#print-a-test-label) or [void](#void-a-shipping-label) it from the order page.

>Information:
>Shipping rates are calculated based on the weight of the products you're shipping. If you [add product weights](/manual/products/add-update-products) when you create new products or [use the bulk editor](/manual/productivity-tools/bulk-editing-products) to update the product weights in your current inventory, then you're more likely to receive correct shipping rates when you're fulfilling your orders.

{{ 'WQUQHB0Ow5Q' | youtube }}

{% include link-to-more-videos.md %}

## Print a test label

You can print a test shipping label to make sure that your printer is set up properly. You will not be charged for printing a test label.

>Information:
>You can also print a test label by visiting the [test label page](https://cdn.shopify.com/s/assets/admin/shipping/test-label--usps-4_x_6_PNG-7ec2736fc2f2217940be4a8a4d28cc623f0f0a7d4485eed298c30ade84db013a.pdf) directly.

#### Steps:

{% sections "Desktop, iPhone, Android" %}

1. From your Shopify admin, click **Settings**, and then click **Shipping**.

2. In the **Shipping labels** section, click **Print test label**.

3. If the label downloads to your computer, then find the file on your computer and open it. If the label opens in a new tab in your browser, then open the tab.

4. Find the print option for the test label, then select it.

5. In the print dialog, select the printer you want to use to print the label.

6. Select the paper size that matches the printer you're using to print the label. If you're [using a label printer](/manual/shipping/shopify-shipping/label-printers), then select **4" x 6"**. If you're using a desktop printer, select **8.5" x 11"**.

7. After you've chosen the correct printer and paper size, click **Print**.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), go to **Store** > **Settings**.

2. Under **Store settings**, tap **Shipping**.

3. In the **Label format** section, select the correct paper size for your printer. If you're [using a label printer](/manual/shipping/shopify-shipping/label-printers), then select **4" x 6"**. If you're using a desktop printer, then select **8.5" x 11"**.

4. Tap **Print test label**.

5. Tap **Printer**, then select your printer.

6. Tap **Print**.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), go to **Store** > **Settings**.

2. Under **Store settings**, tap **Shipping**.

3. In the **Label format** section, select the correct paper size for your printer. If you're [using a label printer](/manual/shipping/shopify-shipping/label-printers), then select **4" x 6"**. If you're using a desktop printer, then select **8.5" x 11"**.

4. Tap **Print test label**.

   > Note:
   > If you're using Google Chrome, then your shipping label might automatically download to your device instead of opening a print dialog. Find the file in your **Downloads** folder and open it.

5. Tap <code>&#8942;</code> to expand the menu, then select **Print**:
   ![Expanded drop-down menu showing the "Print" button location](/manual/shipping/shipping-label-print-preview-android.png)

6. In the print preview, select your printer from the drop-down menu, then tap **Print**.

{% endsections %}

## Buy a shipping label

The cost of shipping labels is based on the [rates offered by UPS, DHL, USPS or Canada Post](/manual/shipping/shopify-shipping/rates).

> Note:
> If you are dropshipping, or a third-party ships out products on your behalf, then you don't need to purchase a shipping label unless your fulfillment service requests one. To learn more, visit our [_fulfillment through a third-party service_](/manual/orders/fulfill-orders#fulfillment-through-a-third-party-service) section.

#### Steps:

{% sections "Desktop, iPhone, Android" %}

{% include admin_sidebar/orders.md %}

2.  Click an order that contains unfulfilled items.

3.  In the **Unfulfilled** section, click **Create shipping label**.

4.  In the **Items** section, confirm the number of items you want to include in this fulfillment. If you want to ship the customer's order using more than one fulfillment, then reduce the quantity of each item that you don't want to ship in this fulfillment to zero. You can buy an additional shipping label for each fulfillment that's required to complete the entire order.

5.  Select a package from the **Package** drop-down menu, and then enter the weight of your shipment in the **Total weight** text box:
    ![All fields in the "Package and weight" section](/manual/settings/shipping/shipping-label-package-and-weight.png)
    If you want to add a new package type, then click **Add package**. In the **Add a package** dialog, enter the information about your new package type, and then click **Add package**.

    > Information:
    > Some mail types have restrictions on the size of the packages that you can use to ship your products. A notice about applicable size restrictions will appear on the **Add a package** dialog when you create a new package type.

3.  Select a shipping method in the **Shipping Service** section.

4.  If you're shipping internationally, then you need to complete the **Customs declaration** form:
    ![Highlighted location of the "Edit customs information" button](/manual/shipping/customs-information.jpg)

    > Note:
    > You can find the required customs codes using the United States Trade Commission [HTS search](https://hts.usitc.gov/). Harmonized System (HS) codes are 6-digit numbers used internationally to classify goods for trade and customs. Learn more about HS codes from the [World Customs Organization](http://www.wcoomd.org/en/topics/nomenclature/overview/what-is-the-harmonized-system.aspx).

5.  If you're using Shopify Shipping with [UPS](manual/shipping/shopify-shipping/shipping-options#signature-required-ups-specific), [USPS](/manual/shipping/shopify-shipping/shipping-options/#signature-confirmation-usps-specific), or [Canada Post](/manual/shipping/shopify-shipping/shipping-options/#signature-required-canada-post-specific), then Check **Signature Confirmation** or **Signature required** to require a signature upon delivery.

6.  If you're using Shopify Shipping, then you can set a shipping date and click **Send shipment details to your customer** to automatically send shipment details to your customers on that date:
![All fields in the "Shipping date" section](/manual/settings/shipping/shipping-date.png)

8.  If you're using Shopify Shipping with UPS, then you need to accept the Shopify Shipping UPS Terms.

7.  Review your shipping details in the **Summary** section, and then click **Buy shipping label**.

When you're ready to ship your order, you might be required to [print out the customs form](#print-a-customs-declaration-form) separately and affix it to the outside of your package.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), tap **Orders**.

2. Tap the order that you want to fulfill.

3. In the **Unfulfilled** section, tap **Create shipping label**.

4. In the **Shipping address** section, confirm the customer's shipping address. Tap **Edit shipping address** to change the shipping address or customer name.

5. In the **Items** section, enter the quantity of each item that you want to include in the shipment. By default, all the order's unfulfilled items are included in the fulfillment.

6. In the **Package and weight** section, select a package from the **Package** drop-down menu, then enter the weight of your shipment in the **Total weight** field. If you want to add a new package, then tap **Add package** and enter the new package size and weight.

   > Information:
   > Some mail types have restrictions on the size of the packages that you can use to ship your products. A notice about applicable size restrictions will appear on the **Add a package** dialog when you create a new package type.

7. In the **Shipping service** section, select a shipping carrier.

8. Optional: Uncheck **Email shipment details to customer now**.

9. Tap **Buy shipping label**.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), tap **Orders**.

2. Tap the order that you want to fulfill.

3. In the **Unfulfilled** section, tap **CREATE SHIPPING LABEL**.

4. In the **Shipping address** section, confirm the customer's shipping address. Tap **Edit shipping address** to change the shipping address or customer name.

5. In the **Items** section, enter the quantity of each item that you want to include in the shipment. By default, all the order's unfulfilled items are included in the fulfillment.

6. In the **Package and weight** section, select a package from the **Package** drop-down menu, then enter the weight of your shipment in the **Total weight** field. If you want to add a new package, then tap **Add package** and enter the new package size and weight.

   > Information:
   > Some mail types have restrictions on the size of the packages that you can use to ship your products. A notice about applicable size restrictions will appear on the **Add a package** dialog when you create a new package type.

7. In the **Shipping service** section, select a shipping carrier.

8. Optional: Uncheck **Email shipment details to customer now**.

9. Tap **Buy shipping label**.

{% endsections %}

> Note:
> The cost of Canada Post shipping labels is displayed in CAD, but converted to USD when you are billed through your Shopify account.

After you buy a shipping label, the cost is billed to you through your Shopify account. The total price will appear on your bill and includes any applicable taxes and fees.

> Tip:
> Not all packaging types are eligible to receive a USPS tracking number. For example, package tracking isn't supported for the First Class Large Envelope (flat) package type. To learn more, [compare the services that USPS offers for each packaging type](//www.usps.com/ship/insurance-extra-services.htm) (click **Quick Compare**).

### Print a shipping label

After you buy a shipping label, you need to print it out and affix it to the outside of the package you want to ship.

If you're shipping internationally, then your package might need a separate [customs declaration form](#print-a-customs-declaration-form) too.

You can print shipping labels using a [supported label printer](/manual/shipping/shopify-shipping/label-printers), or you can print them using a desktop printer and affix them to the outside of your package using a plastic sleeve or packing tape. If you need to change the format of a shipping label after you've purchased it, then change the label format in your [**Shipping**](//www.shopify.com/admin/settings/shipping) settings, and reprint the label.

#### Steps:

{% sections "Desktop, iPhone, Android" %}

{% include admin_sidebar/orders.md %}

2. Click the number of an order that you've purchased a shipping label for.

3. Click **More actions**, and then click **Print label**:
   ![Highlighted location of the "Print label" button](/manual/settings/shipping/download-label.png)

4. In the dialog, select the printer that you want to use to print the label.

5. Select the a paper size that matches the printer you're using to print the label. If you're [using a label printer](/manual/shipping/shopify-shipping/label-printers), then select **4" x 6"**. If you're using a desktop printer, then select **8.5" x 11"**.

6. After you've chosen the correct printer and paper size, click **Print**.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), tap **Orders**.

2. Tap an order that you've purchased a shipping label for.

3. In the **Fulfilled** section, tap **Print shipping label**.

4. Tap **Printer**, then select your printer.

5. Tap **Print**.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), tap **Orders**.

2. Tap an order that you've purchased a shipping label for.

3. In the **Fulfilled** section, tap **PRINT SHIPPING LABEL**.

   > Note:
   > If you're using Google Chrome, then your shipping label might automatically download to your device instead of opening a print dialog. Find the file in your **Downloads** folder and open it.

4. Tap <code>&#8942;</code> to expand the menu, then select **Print**:
   ![Expanded drop-down menu showing the "Print" button location](/manual/shipping/shipping-label-print-preview-android.png)

5. In the print preview, select your printer from the drop-down menu, then tap **Print**.

{% endsections %}

### Print a customs declaration form

If you're shipping to an international destination, then you need to complete a customs declaration form. Some mail types require that you print a separate customs form for your shipment, and others include the form on the standard shipping label:

* If you use **Priority Mail International** or **Priority Express Mail International**, then you need to print a separate customs form in addition to the shipping label and affix them both to the outside of your package.
* If you use **First Class Package International Service**,  **Priority Mail Flat International flat rate envelopes**, or **Priority Mail International small flat rate boxes**, then the customs declaration is included in the shipping label itself.

> Note:
> If you [buy and print multiple shipping labels](#buy-and-print-multiple-shipping-labels) at once, then you can also print any necessary customs declaration forms during that process.

#### Steps:

{% sections "Desktop, iPhone, Android" %}

{% include admin_sidebar/orders.md %}

2. Click the number of an international order that needs a separate customs declaration form.

3. Click **More actions**, and then click **Create shipping label**:
   ![Highlighted location of the "Create shipping label" button](/manual/settings/shipping/fulfill-items-customs.png)

4. In the **Items** section, click **Edit customs information**:
   ![Highlighted location of the "Edit customs information" button](/manual/settings/shipping/customs-information.png)

5. Fill out the **Edit customs information** form, then click **Save**:
   ![All fields in the "Edit customs information" section](/manual/settings/shipping/customs-information-popup.png)

6. When you are ready to purchase the label, click **Buy shipping label**:
   !["Buy shipping label" button in the Summary section](/manual/settings/shipping/customs-buy-label.png)

7. Click **Print label**.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), tap **Orders**.

2. Tap an order that needs a separate customs declaration form.

3. In the **Unfulfilled** section tap **Create shipping label**.

4. In the **Items** section, tap **Edit customs information**.

5. Fill out the customs information form, then tap **Save**:
   ![All fields in the "Edit customs information" section](/manual/shipping/create-shipping-label-edit-customs-iphone.png)

6. Tap **Buy shipping label** when you are ready to purchase the label.

7. Tap **Print shipping label**.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), tap **Orders**.

2. Tap an order that needs a separate customs declaration form.

3. In the **Unfulfilled** section tap **CREATE SHIPPING LABEL**.

4. In the **Items** section, tap **Edit customs information**.

5. Fill out the customs information form, then tap **Save**:
   ![All fields in the "Edit customs information" section](/manual/shipping/create-shipping-label-edit-customs-android.png)

6. Tap **Buy shipping label** when you are ready to purchase the label.

7. Tap **Print shipping label**.

{% endsections %}

The customs declaration form will be printed with the shipping label.

>Note:
>International labels can't be purchased using Shopify Shipping if the line items are valued over $2,500 USD.

## Buy and print multiple shipping labels

You can buy and print up to 20 shipping labels at a time from the [**Orders**](//www.shopify.com/admin/orders) page in your Shopify admin. Use the checkboxes to select up to 20 orders that you want to buy shipping labels for.

The following kinds of orders won't be included when buying shipping labels in bulk:

  * orders that contain only items that do not require shipping
  * orders that don't have a valid shipping address
  * orders that are already fulfilled

If an order has already been partially fulfilled, then only the unfulfilled items are included in the bulk label purchase.

## Shipping label format

The format of a shipping label depends on which carrier and class you choose when you're buying a label. You can't edit the label format because each carrier has specific requirements for their labels.

If you purchase a label using Shopify Shipping, then it will include the order number that's in your Shopify admin. You can use the order number on the label to match packages to orders more easily. The placement of the order number varies between carriers:
![Highlighted order number location on an example USPS label](/manual/settings/shipping/order-label-usps.png)
![Highlighted order number location on an example DHL label](/manual/settings/shipping/order-label-dhl.png)

>Note:
>The order number doesn't appear on USPS First Class Package International labels.

To minimize the risk of shipping delays, when you affix the label to the package, all barcodes should be easy to scan. Specifically, you should make sure that barcodes on a shipping-tube label run lengthwise along the tube.

## Change your shipping label printer settings

If you print a shipping label using the wrong printer settings, then you can change your label settings to the correct printer type, and reprint the shipping label.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2.  In the **Shipping labels** section, select the **Label format** that matches the printer you want to use:
    ![All fields in the "Label format" section](/manual/settings/shipping/printer-type.png)

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

After you've changed your label printer settings, you can reprint the shipping label whose format you want to change. You don't need to void and repurchase the label before you reprint it in the new format.

## Void a shipping label

You can void a shipping label after you've bought it, as long as:

* it's been less than 30 days since you bought the label
* the package hasn't already been shipped by your carrier.

After you void a shipping label, the cost of the label is credited to your account. This amount will be applied to the cost of any shipping labels that you buy in the future. If the package has been shipped, then contact the carrier with the package reference number for help.

{{ 'tc7B1_r5v-Y' | youtube }}

{% include link-to-more-videos.md %}

To void a shipping label:

{% sections "Desktop, iPhone, Android" %}

{% include admin_sidebar/orders.md %}

2. Click the number of the order with the shipping label that you want to void.

3. In the **Fulfilled** section, click **More**, and then click **Void label**:

   > Note:
   > You can also void a shipping label from the **Timeline** section of an order's page using the **Manage shipment** drop-down menu.

4. Select a **Reason for voiding** from the drop-down-menu:
   ![Highlighted "Reason for voiding" drop-down menu](/manual/settings/shipping/reason-for-voiding.png)

5. Click **Void label** to confirm.
   You can [buy a new label for this order](#buy-a-shipping-label) from the order details page.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), tap **Orders**.

2. Tap the order with the shipping label you want to void.

3. In the **Fulfilled** section, tap `...` to expand the shipping label menu.

4. Tap **Void shipping label**.

5. Select a **Reason for voiding**.

6. Tap **Void label** to confirm.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), tap **Orders**.

2. Tap the order with the shipping label you want to void.

3. In the **Fulfilled** section, tap <code>&#8942;</code> to expand the shipping label menu.

4. Tap **Void shipping label**.

5. Select a **Reason for voiding**.

6. Tap **Void label** to confirm.

{% endsections %}
