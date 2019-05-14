---
url: /en/manual/shipping/understanding-shipping/initial-setup
gid: e80a950b-688d-488a-b89a-1ccc4231b9f2
title: Initial setup
short_title: Initial setup
description: Set up the dispatch address and shipping zones for your online Shopify store.
legacy-urls:
  - /manual/shipping/initial-shipping-setup
weight: 2
keywords:
  - zones
  - set up
  - setup
  - addresses
  - packages
  - shipping
---

Before you can start shipping your products, you need to add some information about your business on the [**Shipping**](//www.shopify.com/admin/settings/shipping) page in your Shopify admin.

To find the **Shipping** settings page:

From your Shopify admin, click **Settings**, and then click **Shipping**.

## Add a shipping origin address

If you ship your products from somewhere other than your store's main office, you can specify a separate shipping origin to make sure your taxes and [calculated shipping rates](/manual/shipping/rates-and-methods/custom-calculated-rates) are correct.

> Note:
> If you're tracking inventory at [multiple locations](/manual/locations), then these steps don't apply. Instead, your store address is used as the shipping origin, which is used when calculating shipping rates and creating shipping labels.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Shipping origin** section, click **Edit address**: {{ '/manual/settings/shipping/update-shipping-address.png' | image }}

3. Enter the address of the location where you ship your products from, and then click **Save**: {{ '/manual/settings/shipping/update-shipping-address-save.png' | image }}

## Change the shipping origin

> Note:
> These steps apply only if you are using [multiple locations](/manual/locations).

After you enable multiple locations, your shipping rates are calculated based on the location that is set as the shipping origin.

You can set any of your active locations to be the shipping origin. However, apps and deactivated locations can't be set as the shipping origin.

If you change the shipping origin to a location where a carrier isn't supported, then the rates for that carrier are hidden at the checkout. For example, if you set the shipping origin to a location that is in the United States, then Canada Post rates aren't displayed at the checkout.

Rates for buying shipping labels from the Shopify admin are calculated based on the fulfillment location, not the shipping origin.

#### Steps:

{% sections "Desktop, iPhone, Android" %}

1. Go to **Settings** > **Shipping**.

2. In the **Shipping from** section, click **Change shipping origin**.

3. Select a location, and then click **Save**.

----

{% include shipping/change-shipping-origin-mobile.md %}

----

{% include shipping/change-shipping-origin-mobile.md %}

{% endsections %}

## Add a package type

If your store is in the United States or Canada, then you can save the dimensions and weights of your preferred package types on the [**Shipping**](//www.shopify.com/admin/settings/shipping) settings page in your Shopify admin.

>Information:
>If you enter dimensions and weights for your packages, then your [calculated shipping](/manual/shipping/rates-and-methods/custom-calculated-rates) rates will be more accurate.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Packages** section, click **Add package**: {{ '/manual/settings/shipping/add-package.png' | image }}

3. In the dialog, enter the required information about the package type: {{ '/manual/settings/shipping/add-a-package.png' | image }}
  Some mail types have restrictions on the size of the packages that you can use to ship your products. A notice about applicable size restrictions will appear on the dialog when you create a new package type.

>Information:
>If your store is based in the United States, then you can [add USPS flat rate packaging](/manual/shipping/understanding-shipping/packaging-and-weights/#usps-flat-rate-packaging).

4. Click **Add package**.

>Note:
>Advertised box dimensions may refer to the inside of the packaging, so it's important to measure the outside dimensions of your boxes.

## Edit or delete a package type

You can edit or delete an existing package type by clicking on its name in the **Packages** section.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Packages** section, click **Edit** next to the package type that you want to edit: {{ '/manual/settings/shipping/edit-package.png' | image }}

3. In the dialog, enter your changes and then click **Save**, or click **Delete package**: {{ '/manual/settings/shipping/edit-rate-dialog.png' | image }}

## Next steps

Before you can start shipping your customers orders, you need to:

* [add a shipping zone](/manual/shipping/zones)
* [set shipping rates](/manual/shipping/rates-and-methods).
