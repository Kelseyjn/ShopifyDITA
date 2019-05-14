---
url: /en/manual/shipping/rates-and-methods/custom-calculated-rates/canada-post
gid: a813644c-270e-4f05-89f1-9ea56402e86c
title: Activate shipping with Canada post
short_title: Canada Post
description: Use Canada Post to show your customers calculated rates when they check out from your Shopify store.
legacy-urls:
  - /manual/shipping/rates-and-methods/calculated-rates/canada-post
  - /manual/shipping/rates-and-methods/carriers/canada-post
  - /manual/shipping/rates-and-methods/custom-carrier-accounts/canada-post
  - /manual/shipping/shopify-shipping/carriers
weight: 3
keywords:
  - Canada Post
  - shipping
  - calculated
  - CCS
  - Shopify Shipping
  - rates
  - zones
  - negotiated
---

If you have a custom account with Canada Post, then you can display calculated shipping rates to your customers at checkout.

>Growth:
>You can display calculated rates to your customers from Canada Post using [Shopify Shipping](/manual/shipping/shopify-shipping) on all plans. You don't need to have an account with Canada Post and rates are included by default in your Shopify admin.

{% comment %}
## Add Canada Post calculated rates to zones

If you're using Shopify Shipping, then you can display calculated shipping rates to your customers at checkout.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Zones and rates** section, click **Edit** next to the shipping zone that you want to add the rate to: {{ '/manual/settings/shipping/zone-edit-CP.png' | image }} If you want to add a rate to a new zone, then you'll need to [create a new shipping zone](/manual/shipping/zones/#create-a-new-shipping-zone) first.

3. In the **Calculated rates** section, click **Add rate**: {{ '/manual/settings/shipping/add-calc-rate-cp.png' | image }}

4. In the dialog, select **Canada Post (Discounted rates from Shopify Shipping)** in the **Select a carrier** field.

5. Check the mail classes that you want to offer to your customers in the **Services** section: {{ '/manual/settings/shipping/ccs-mail-class-cp.png' | image }} {% block "note" %}
Shopify Shipping doesn't offer Regular Parcel rates. The Expedited Parcel rates cost less and deliver faster with Shopify Shipping.
{% endblock %}

6. Check **Automatically offer new shipping services when they become available** in the **Future services** section to include new mail classes by default when they become available.

7. In the **Rate adjustments** section, enter a dollar or percentage value if you want to add a markup to the calculated rate: {{ '/manual/settings/shipping/css-usps-adjustment.png' | image }}

8. Click **Done**:{{ '/manual/settings/shipping/weight-based-manual-save-cp.png' | image }}

9. Click **Save** at the bottom of the shipping zone page.

{% endcomment %}

## Use your own Canada Post account

>Note:
>This feature requires that your store is on the Advanced Shopify plan, is on the Shopify Plus plan, or has the calculated shipping plan upgrade.

If you've negotiated discounted shipping rates with Canada Post, then you can display your negotiated rates at checkout by connecting your Canada Post [Solutions for Small Business](//www.canadapost.ca/smallbusiness) account with your Shopify account.

After you connect your accounts, your negotiated rates will be offered to your customers at checkout. These rates will not replace the rates of the shipping labels that you can buy in your Shopify admin by using [Shopify Shipping](/manual/shipping/shopify-shipping).

>Caution
>If your store processes a high volume of orders, then you need to [request an API rate limit increase from Canada Post](//www.canadapost.ca/cpotools/apps/drc/increaseLimits?execution=e1s1). By default, the Canada Post API provides quotes for only up to 20 shipping rates per minute. If Canada Post approves your request for an API rate limit increase, then your account can retrieve up to 400 shipping rates per minute.


#### Steps:

1. Log in to the Canada Post [Developer Program website](//www.canadapost.ca/cpotools/apps/drc/home) using the username and password for your Canada Post Solutions for Small Business account. If you already have an account, then select your account number from the dropdown list. If you don't have an account yet, then click **Join now** instead.

2. On the **Welcome** page, copy the username and password that appear in the **Production** section of the **API Keys** table. These are included in the **Key Number**: {{ '/manual/settings/shipping/cp-api-keys.png' | image }}
  The **Key Number** includes two parts, which are separated by a `:`. The first part is your **username**, and the second part is your **password**. Make sure that you don't include the `:` character when you copy your username and password.

{% include admin_sidebar/settings-shipping.md %}

3. In the **Carrier accounts** section, click **Connect carrier account**.

4. Click **Connect account** beside **Canada Post**.

5. On the **Connect Canada Post** dialog, enter your account information (including the username and password that you copied from your Canada Post Developer Program account).
  <table>
    <tr>
      <th>Customer Number</th>
      <td>The customer number of your Canada Post Solutions for Small Business account.</td>
    </tr>
    <tr>
      <th>Production Password</th>
      <td>The password that's included in your <strong>Key Number</strong>. You can find this in the **API Keys** table in your Canada Post Developer Program account.</td>
    </tr>
    <tr>
      <th>Production Username</th>
      <td>The username that's included in your <strong>Key Number</strong>. You can find this in the **API Keys** table in your Canada Post Developer Program account.</td>
    </tr>
    <tr>
      <th>Contract Number (optional)</th>
      <td>The number for your contract shipping account (optional).</td>
    </tr>
  </table>

6. If you want to add your negotiated rates to your existing shipping zones, then check **Add rates to existing shipping zones**. This will replace your current Canada Post rates and adds them to all shipping zones, even those that you don’t currently use for Canada Post rates.

7. Click **Save**.

8. If your store processes a high volume of orders, then you need to [request an API rate limit increase from Canada Post](//www.canadapost.ca/cpotools/apps/drc/increaseLimits?execution=e1s1). By default, the Canada Post API provides quotes for only up to 20 shipping rates per minute. If Canada Post approves your request for an API rate limit increase, then your account can retrieve up to 400 shipping rates per minute.
