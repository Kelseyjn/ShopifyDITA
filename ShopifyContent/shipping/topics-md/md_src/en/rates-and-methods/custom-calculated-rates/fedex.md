---
url: /en/manual/shipping/rates-and-methods/custom-calculated-rates/fedex
gid: 2b7420bf-fc08-4816-9148-788340ab3fb5
title: Activate shipping with Fedex
short_title: FedEx
description: Activate calculated shipping with FedEx for your online Shopify store.
legacy-urls:
  - /manual/shipping/rates-and-methods/calculated-rates/fedex
  - /manual/shipping/rates-and-methods/carriers/fedex
  - /manual/shipping/rates-and-methods/custom-carrier-accounts/fedex
weight: 5
keywords:
  - FedEx
  - carriers
  - third-party
  - third party
  - carrier-calculated
  - calculated
  - rates
  - carrier calculated
  - credentials
  - shipping
---
>Note:
>This feature requires that your store is on the Advanced Shopify plan, is on the Shopify Plus plan, or has the calculated shipping plan upgrade.

If you've negotiated a discounted rate with FedEx, then you can enter your account number when you [activate your FedEx service](#activate-calculated-shipping-for-fedex) so that the discounted rate appears to your customers at checkout.

You'll need an account with FedEx before you can activate this carrier service on your Shopify store.

>Growth:
>You can display calculated rates to your customers from USPS, DHL Express, UPS, and Canada Post using [Shopify Shipping](/manual/shipping/shopify-shipping).


## Register for an account with FedEx

#### Steps:

{% include password-disclaimer.md %}

1. Visit the [FedEx website](//www.fedex.com) and click the country where your store is located.

2. Click **Sign Up or Log In**.

3. Click **Open an account**.

4. Fill in the registration form.

5. In the **Confirm Your Selected Account Options** section of the registration form, select **Open a FedEx account**.

6. Click **Continue**.


During the setup process with FedEx, make note of the account number that you are assigned and make sure your billing address is correct.

You will need to re-enter this information later and the details must match exactly.


## Obtain your FedEx credentials

Before you obtain your credentials, make sure that you have an [account with FedEx](#register-for-an-account-with-fedex).

#### Steps:

1. Visit the [FedEx Web Services website](http://www.fedex.com/developer).

2. Log in using your FedEx account login and password.

3. Click **Technical Resources**, and select **FedEx Web Services for Shipping**.

4. Select **Move to Production**.  

5. Click **Obtain Production Key**.

6. Complete the **Developer Resource Center Registration** form, and accept the terms and conditions.

7. Record your **Developer Test Key**, **Test Account Number**, and **Test Meter Number** at the end of your registration process.

    {% block "note-caution" %} Your Meter Number will be emailed to you by FedEx, but the authentication key will not. Make sure that you **record your authentication key** before proceeding.{% endblock %}

8. Check for an email from FedEx that includes your **Key Password**, **Account Number**, and **Meter Number**.

9. Record all of this information because you need it to activate FedEx in the Shopify admin.


## Activate calculated shipping for FedEx

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

3. In the **Carrier accounts** section, click **Connect carrier account** or **Manage carriers**.

3. Click **Connect account** beside **FedEx**.

4. On the **Connect FedEx** dialog, enter your FedEx credentials.  

5. Optional: If you've enabled FedEx SmartPost rates with FedEx, then enter your SmartPost Hub ID to show your negotiated rates at checkout.

5. Click **Save**.

>Note:
>If your Shopify account is frozen at any time, your carriers might become deactivated. Check your shipping settings as soon as your account is restored.
