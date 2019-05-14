---
gid: 9c59b9dc-96b7-4168-b821-214f4ccc98b3
url: /en/manual/shipping/shopify-shipping/return-labels
title: Return labels
description: Create and send return labels from your Shopify admin or the Shopify app.

weight: 4

keywords:
  - return labels
  - returns
  - refund
  - paying for return labels

---

> Note:
> Return labels are only available for US domestic orders. US military addresses or US territories that require a customs form aren't supported.

To offer returns to your customers, you can create and send return labels in your Shopify admin. After you create a return label, you can send it by email directly from the Shopify admin or copy a link to print the label.

When you are creating a return label, you can select the shipping method and use your discounted shipping rates from USPS. If you’ve [connected your UPS account to Shopify](/manual/shipping/rates-and-methods/custom-calculated-rates/ups), then you can [create UPS return labels using your own account rates](/manual/shipping/rates-and-methods/custom-calculated-rates/ups/buy-labels-with-your-ups-account) and you are billed directly by UPS.

## Setting up your return policy

Before you create return labels consider adding information about returns to your [refund policy in your Shopify store](/manual/checkout-settings/refund-privacy-tos).

## Paying for return labels

Return labels use a technology called pay on scan. This means that the shipping carrier weighs and measures the package when they receive it, and then calculate the cost.

The cost of a return label is only added to your Shopify account after the carrier scans the package. Your account is charged when you reach a billing threshold that's determined by your current Shopify plan. To learn more about how you're billed for shipping labels, contact [Shopify Support](https://help.shopify.com/questions).

>Tip:
>Return labels don't expire and cannot be voided, however you aren't charged for unused labels.

## Create and send return label

You can create a return label from the order page in your Shopify admin or the Shopify app. After you create a return label, you can send it to your customers, or by sending them a link to print the label.

{{ 'q4wfm3pmpNY' | youtube }}

{% include link-to-more-videos.md %}

#### Steps:

{% sections "Desktop, iPhone, Android" %}

{% include admin_sidebar/orders.md %}

2. Click the order number.

3. Click **More actions** > **Create return label**.

4. Select the expected package size.

5. Add the weight of the order to the **expected weight**.

6. Select a shipping method.

7. Click **Create return label**.

8. Select the way you want to share the return label with your customer:
  - Confirm your customer's email and click **Email customer**.
  - Click **Copy link** and send it separately in existing email or message thread.
  - Click **Print label** and send it with the order.

9. Click **Done**.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), tap **Orders**.

2. Tap the order number.

3. Tap **More actions** > **Create return label**.

4. Select the expected package size.

5. Add the weight of the order to the **expected weight**.

6. Select a shipping method.

7. Tap **Create return label**.

8. Select the way you want to share the return label with your customer:
  - Confirm your customer's email and tap **Email customer**.
  - Tap **Copy link** and send it separately in existing email or message thread.
  - Tap **Print label** and send it with the order.

9. Tap **Done**.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), tap **Orders**.

2. Tap the order number.

3. Tap **More actions** > **Create return label**.

4. Select the expected package size.

5. Add the weight of the order to the **expected weight**.

6. Select a shipping method.

7. Tap **Create return label**.

8. Select the way you want to share the return label with your customer:
  - Confirm your customer's email and tap **Email customer**.
  - Tap **Copy link** and send it separately in existing email or message thread.
  - Tap **Print label** and send it with the order.

9. Tap **Done**.

{% endsections %}

## Resend a return label

You can resend the email notification or copy the link to the label at any time.

#### Steps:

{% sections "Desktop, iPhone, Android" %}

{% include admin_sidebar/orders.md %}

2. Click the order number.

3. On the **Return label** section, click **View details**

4. Select the way you want to share the return label with your customer:
  - Confirm your customer's email and click **Email customer**.
  - Click **Copy link** and send it separately in existing email or message thread.
  - Click **Print label** and send it with the order.

5. Click **Done**.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), tap **Orders**.

2. Tap the order number.

3. On the **Return label** section, tap **View details**

4. Select the way you want to share the return label with your customer:
  - Confirm your customer's email and tap **Email customer**.
  - Tap **Copy link** and send it separately in existing email or message thread.
  - Tap **Print label** and send it with the order.

5. Tap **Done**.

----

1. From the [Shopify app](https://www.shopify.com/install/detect), tap **Orders**.

2. Tap the order number.

3. On the **Return label** section, tap **View details**

4. Select the way you want to share the return label with your customer:
  - Confirm your customer's email and tap **Email customer**.
  - Tap **Copy link** and send it separately in existing email or message thread.
  - Tap **Print label** and send it with the order.

5. Tap **Done**.

{% endsections %}


## Customize your return label instructions

{% include admin_sidebar/settings-notifications.md %}

2. In the **Customer Notification** section, under **Shipping**, click **Return label instructions**.

3. Edit the **Email subject** and **Email body**. For example, if you want to change the return instructions, then find `return-label__instruction-step` and edit the steps.

4. Click **Save**.

For more information about using Liquid variables to automatically add information to your return label instructions, see the [notification variables reference](/manual/sell-online/notifications/email-variables).

## Frequently asked questions

### Can I void an unused label?
No. Return labels don't expire and cannot be voided, however you aren't charged for unused labels.

### Why can't I see Create return label on the order page?
If you don’t see the **Create return label** option in the **More actions** menu, then you might not have any fulfilled items. Creating a return label requires at least one item to be fulfilled.

Your store also may not be eligible for return labels. To qualify, your shipping origin must be located in the United States. [Learn how to change your shipping origin](https://help.shopify.com/en/manual/shipping/understanding-shipping/initial-setup#change-the-shipping-origin).

### Can I create a return label for an international order?
No. Return labels are only available for domestic orders at this time.
