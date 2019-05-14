---
url: /en/manual/shipping/zones
gid: 63e29357-13ad-4c03-8779-d5f87f8b129c
title: Shipping zones
description: Choose the destinations where you want to ship your store's products.
legacy-urls:
  - /manual/shipping/managing-shipping/zones
weight: 3
fullstory: true
keywords:
    - set up
    - setup
    - zones
    - zip
    - post
    - postal
    - codes
    - locations
    - addresses
    - countries
    - regions
    - shipping
---

The regions and countries that you ship to are known as shipping zones. Each shipping zone includes shipping rates that apply to customers whose addresses are within that zone. You can see your current shipping zones and shipping rates on the [**Shipping**](//www.shopify.com/admin/settings/shipping) page in your Shopify admin.

> Note:
> If a customer enters a shipping address that's in a region outside your shipping zones, then they'll be informed that no shipping rate is available for their area.

## Create a new shipping zone

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Zones and rates** section, click **Add shipping zone**. {{ '/manual/settings/shipping/add-shipping-zone.png' | image }}

3. In the **Zone name** section, enter a name for your new shipping zone. {{ '/manual/settings/shipping/new-shipping-zone-name.png' | image }}

4. Click **Add countries** in the **Countries** section.
  {% block "note-caution" %}
  Your default tax rates are based on your shipping zones. If you make an update to your shipping zones, then make sure to [review your tax settings](/manual/taxes/#general-process-to-set-up-taxes).
  {% endblock %}

5. Select the countries that you want to include in the shipping zone, and then click **Add**. {{ '/manual/settings/shipping/add-destination.png' | image }}
If you select a large region like **North America** or **Europe**, then the shipping zone will include all the countries within that region. You can remove specific countries or regions using the checkboxes beside them.

6. If you want to limit the shipping zone to certain areas within a country, then you can click **Edit** beside the region that you want to change. {{ '/manual/settings/shipping/edit-regions.png' | image }}
  You can add or remove specific states or provinces using the checkboxes beside them, then click **Done**. {{ '/manual/settings/shipping/edit-provinces.png' | image }}
  {% block "note" %}
  Not all countries display separate states or provinces in this section.
  {% endblock %}

7. If you want to [add a manual shipping rate](/manual/shipping/rates-and-methods/manual-rates) to the shipping zone, then click **Add rate** for the type of rate that you want to create. {{ '/manual/settings/shipping/pick-rate-type.png' | image }} You can add shipping rates later if you want. {% block "note" %}
If you use [Shopify Shipping](/manual/shipping/shopify-shipping), then you can [add calculated rates](/manual/shipping/shopify-shipping/setting-up-shopify-shipping/#add-calculated-rates-to-zones) to your shipping zones at this time.
{% endblock %}

8. When you're done, click **Save**. The new shipping zone will appear on the [**Shipping**](//www.shopify.com/admin/shipping) settings page in your Shopify admin.

## Add or remove a country or region from an existing shipping zone

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Zones and rates** section, click **Edit** for the shipping zone that you want to change. {{ '/manual/settings/shipping/edit-shipping-zone.png' | image }}

3. In the **Countries** section, click **Add countries** to add a new country to the shipping zone, or click the `x` icon beside a country to remove it from the shipping zone. {{ '/manual/settings/shipping/edit-regions2.png' | image }}
  {% block "note-caution" %}
  Your default tax rates are based on your shipping zones. If you make an update to your shipping zones, then make sure to [review your tax settings](/manual/taxes/#general-process-to-set-up-taxes).
  {% endblock %}

4. When you're done, click **Save**.

{% block "note" %}
Remember to disable all [calculated shipping rates](/manual/shipping/rates-and-methods/custom-calculated-rates) for any countries that you don't want to ship to.
{% endblock %}

## Delete a shipping zone from your shipping list

If you don't want to ship to customers in a certain zone any more, then you can delete that shipping zone from your shipping list. When you delete a shipping zone, it also deletes all the shipping rates you've set for that zone.

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

2. In the **Zones and rates** section, click **Edit** next to the shipping zone that you want to delete. {{ '/manual/settings/shipping/edit-shipping-zone.png' | image }}

3. Click **Delete zone**.

4. Click **Delete shipping zone** to confirm. {{ '/manual/settings/shipping/delete-shipping-zone.png' | image }}

## Creating shipping zones based on postcode or zip code

There are apps that you can use to organize your shipping zones according to postal codes or ZIP codes. Visit the [app store](//apps.shopify.com/) to find out what's available.

## Next steps

* [Add a shipping rate to one of your shipping zones](/manual/shipping/rates-and-methods/manual-rates)
* [Activate an on-demand delivery service](/manual/shipping/on-demand-deliveries)
* [Set up Shopify Shipping to buy and print shipping labels in your Shopify admin](/manual/shipping/shopify-shipping)
