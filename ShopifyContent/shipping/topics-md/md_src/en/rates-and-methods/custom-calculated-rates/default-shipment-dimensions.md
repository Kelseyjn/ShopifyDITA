---
url: /en/manual/shipping/rates-and-methods/custom-calculated-rates/default-shipment-dimensions
gid: b06ee51f-7560-4970-9764-1a216bfd6155
title: Using dimensional weight for calculated shipping rates
short_title: Default shipment dimensions
description: Some carriers use their own formulas to determine rates for very large packages.
legacy-urls:
  - /manual/shipping/rates-and-methods/calculated-rates/default-shipment-dimensions
  - /manual/shipping/rates-and-methods/carriers/default-shipment-dimensions
  - /manual/shipping/rates-and-methods/custom-carrier-accounts/default-shipment-dimensions
weight: 6
keywords:
    - dimensions
    - shipments
    - default
    - packages
    - weights
    - calculated
    - carriers
    - shipping
    - rates
---

Many carriers now calculate shipping rates based on the dimensional or volumetric weight of your shipments. The dimensional weight is calculated according to a formula which uses your default shipment dimensions.

If you use one default box size to ship your orders, then your **Default shipment dimensions** will generate correct [calculated shipping rates](/manual/shipping/rates-and-methods/custom-calculated-rates). If you ship packages in more than one box size, then you should use an app for greater accuracy.

## How dimensional rates work

Your default package dimensions are sent to your shipping carrier along with your order's weight to calculate shipping rates for your customer. Dimensional weight is determined by the carrier based on the height, width, and depth of your packages.

If your dimensional weight is larger than your order's weight, then your customer will be charged for the dimensional weight of their order. If you feel that the generated rates are too high or too low, then you can [adjust your calculated rates](/manual/shipping/rates-and-methods/custom-calculated-rates) to increase or decrease your shipping rates as needed.

Dimensional weight calculations vary between carriers. Consult the carrier you're using for details about their dimensional weight policies.

Carriers with dimensional weight policies:

<ul>
<li><a href="http://www.fedex.com/ae/tools/dimweight.html">FedEx</a></li>
<li><a href="//www.ups.com/content/us/en/resources/ship/packaging/dim_weight.html">UPS</a></li>
<li><a href="//www.canadapost.ca/tools/pg/manual/PGabcmail-e.asp#1378832">Canada Post</a>
<li><a href="//auspost.com.au/parcels-mail/size-and-weight-guidelines.html">Australia Post</a>
<li><a href="http://pe.usps.com/BusinessMail101?ViewName=Weight">USPS</a></li>
</ul>

Carriers without dimensional weight policies:

<ul>
<li><a href="//www.royalmail.com/personal/help-and-support/tell-me-about-size-and-weight-restrictions">Royal Mail</a>
</ul>

## Configure your default package dimensions

#### Steps:

{% include admin_sidebar/settings-shipping.md %}

3. In the **Packages** section, click the title of the package that's beside the **Default** label: {{ '/manual/settings/shipping/click-default-package.png' | image }}

4. Enter a title, the dimensions, and weight of your default shipment package: {{ '/manual/settings/shipping/edit-default-package.png' | image }}

5. Click **Save**.
