---
url: /en/manual/shipping/shopify-shipping/rates
gid: 109fff69-0a10-4a24-8b37-fa8b9dead78a
layout: branching
title: Shipping carriers and example rates
short_title: Shipping carriers and rates
description: View a list of shipping carriers and example Shopify Shipping rates from USPS, UPS, DHL Express, and Canada Post.
buttons: USPS, UPS, DHL Express, Canada Post
legacy-urls:
  - /manual/shipping/labels/rates
weight: 6
keywords:
  - examples
  - rates
  - shipping
  - USPS
  - UPS
  - Canada Post
  - DHL Express
  - international
  - carriers
  - calculated
---

>Note:
>Shopify Shipping is available only to stores based in the United States and Canada.

Depending on your Shopify plan and the order you're shipping, you might be eligible for reduced shipping rates from **USPS**, **UPS**, **DHL Express**, and **Canada Post**. After you've [set up shipping label printing](/manual/shipping/shopify-shipping/buy-and-print) in your Shopify admin, you can view and compare calculated shipping rates from an order's **Fulfillment** page.

The following table shows the maximum discount available by carrier for 2019:

<table>
  <tr>
    <th>Shipping carrier</th>
    <th>Maximum possible discount</th>
  </tr>
  <tr>
    <td>UPS</td>
    <td>Up to 55%</td>
  </tr>
  <tr>
    <td>USPS</td>
    <td>Up to 27%</td>
  </tr>
  <tr>
    <td>DHL Express</td>
    <td>Up to 72%</td>
  </tr>
  <tr>
    <td>Canada Post</td>
    <td>Up to 23%</td>
  </tr>
</table>

For more detailed examples of domestic and international carrier rates for 2019, select a carrier and see below.

----

## Cubic pricing with USPS Priority Mail

>Note:
>Cubic pricing is available only on the Shopify plan or higher.

USPS offers discounted rates on [Priority Mail](#priority) for [packages](#calculating-cubic-pricing-for-packages) and [envelopes](#calculating-cubic-pricing-for-soft-pack-and-padded-envelopes) that weigh less than 20 pounds and that measure less than 0.5 cubic feet in volume. Consider using cubic pricing if you typically send small and heavy products such as weights or coffee beans.

If Shopify calculates a cubic price that's higher than the regular Priority Mail price, then Shopify selects the cheaper rate.

{{ 'Veq8Ggk4kaU' | youtube }}

{% include link-to-more-videos.md %}

### Calculating cubic pricing for packages

Use the following formula to calculate the cubic volume of a package. If the amount is less or equal than 0.5 cubic feet, then the package uses cubic rates. All measurements must be in inches.

**Length (in inches) x Width (in inches) x Height (in inches) / 1728 = cubic feet**

>Note:
>A package doesn't qualify for cubic pricing if any of these measurements is over 18 inches.

For example, you can apply the formula to a standard adult shoe box:

**14" x 8" x 5" / 1728 = 0.3 cubic feet**

This package is less than 0.5 cubic feet and qualifies for cubic rates.

Sample shipment from **N.Y.** to **Chicago** with Shopify Shipping:

<table>
  <tr>
    <th>Cubic volume</th>
    <th>Weight</th>
    <th>Walk-in rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced<br></br>Shopify plan</th>
  </tr>
  <tr>
    <td rowspan="3">0.1<br></br>6 in x 6 in x 4 in</td>
    <td>Light (1 lbs)</td>
    <td>$8.00</td>
    <td>$7.65</td>
    <td>$7.65</td>
    <td>$7.65</td>
  </tr>
  <tr>
    <td>Medium (5 lbs)</td>
    <td>$13.70</td>
    <td>$10.33</td>
    <td>$7.65</td>
    <td>$7.65</td>
  </tr>
  <tr>
    <td>Heavy (10 lbs)</td>
    <td>$26.85</td>
    <td>$19.51</td>
    <td>$7.65</td>
    <td>$7.65</td>
  </tr>
  <tr>
    <td rowspan="3">0.4<br></br>12 in x 9 in x 6 in</td>
    <td>Light (1 lbs)</td>
    <td>$8.00</td>
    <td>$7.65</td>
    <td>$7.65</td>
    <td>$7.65</td>
  </tr>
  <tr>
    <td>Medium (5 lbs)</td>
    <td>$13.70</td>
    <td>$10.33</td>
    <td>$9.50</td>
    <td>$9.50</td>
  </tr>
  <tr>
    <td>Heavy (10 lbs)</td>
    <td>$26.85</td>
    <td>$19.51</td>
    <td>$9.50</td>
    <td>$9.50</td>
  </tr>
</table>

### Calculating cubic pricing for soft-pack and padded envelopes

USPS offers separate cubic pricing for soft-pack and padded envelopes. You can add small boxes to an envelope as long as the envelope keeps its flat shape. Expandable envelopes don't qualify for the envelope pricing and need to use [cubic pricing for packages](#calculating-cubic-pricing-for-packages) instead.

Use the following formula to determine if an empty envelope or soft-pack qualifies for cubic pricing. If the amount is less than 36 inches, then cubic pricing applies.

**Length (in inches) + Width (in inches) = Total package length**

>Note:
>An envelope doesn't qualify for cubic pricing if the length or width is over 18 inches.

<a id="domestic"></a>
## Domestic shipping with USPS

You can ship domestically using [Priority](#priority), [Priority Express](#priority-express), and [First Class](#first-class) mail types.

<table>
  <tr>
    <th>Shipping Service</th>
    <th>Delivery Timeline</th>
    <th>Description</th>
  </tr>

  <tr>
    <td><a href="https://www.usps.com/ship/priority-mail.htm">Priority Mail</a></td>
    <td>1-3 business days</td>
    <td>Ship orders within the U.S. </td>
  </tr>
  <tr>
    <td><a href="https://www.usps.com/ship/priority-mail-express.htm">Priority Mail Express</a>*</td>
    <td>1-2 business days</td>
    <td>The fastest way to ship orders within the U.S.</td>
  </tr>
  <tr>
    <td><a href="https://pe.usps.com/text/dmm300/133.htm">First-Class Package Service</a></td>
    <td>2-3 business days</td>
    <td>An economical way to ship small packages within the U.S.</td>
  </tr>
  <tr>
    <td><a href="https://www.usps.com/ship/first-class-mail.htm">First-Class Mail</a></td>
    <td>2-3 business days</td>
    <td>Ship letters and postcards.</td>
  </tr>
  <tr>
    <td><a href="https://www.usps.com/ship/priority-mail.htm">Parcel Select Ground</a></td>
    <td>2-8 business days</td>
    <td>A reliable and economical way to ship less-than-urgent deliveries and oversized packages. Available online only.</td>
  </tr>
  <tr>
    <td><a href="https://www.usps.com/ship/mail-shipping-services.htm">Media Mail</a></td>
    <td>2-10 business days</td>
    <td>A cost effective way to send media (books, music, and other media) For more information, see the <a href="https://pe.usps.com/text/DMM300/273.htm">USPS approved list for media mail.</a></td>
  </tr>
</table>
\* Guaranteed delivery

>Note:
>All Shopify plans have the same discounted rates from USPS for Priority Mail, Priority Mail Express, First-Class Package Service, and First Class Package International. All other USPS classes have tiered discounts.

<a id="priority"></a>

### Priority Mail rates

Sample shipment from **N.Y.** to **Chicago** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>Walk-in rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td>Light (1 lbs)</td>
    <td>$8.00</td>
    <td>$7.65</td>
    <td>$7.65</td>
    <td>$7.65</td>
  </tr>
  <tr>
    <td>Medium (3 lbs)</td>
    <td>$11.95</td>
    <td>$9.26</td>
    <td>$9.26</td>
    <td>$9.26</td>
  </tr>
  <tr>
    <td>Heavy (5 lbs)</td>
    <td>$13.70</td>
    <td>$10.33</td>
    <td>$10.33</td>
    <td>$10.33</td>
  </tr>
</table>

<a id="priority-express"></a>
### Priority Express Mail rates

Sample shipment from **N.Y.** to **Chicago** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>Walk-in rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td>Light (1 lbs)</td>
    <td>$36.60</td>
    <td>$32.11</td>
    <td>$32.11</td>
    <td>$32.11</td>
  </tr>
  <tr>
    <td>Medium (3 lbs)</td>
    <td>$47.10</td>
    <td>$40.43</td>
    <td>$40.43</td>
    <td>$40.43</td>
  </tr>
  <tr>
    <td>Heavy (5 lbs)</td>
    <td>$57.20</td>
    <td>$49.01</td>
    <td>$49.01</td>
    <td>$49.01</td>
  </tr>
</table>

<a id="first-class"></a>
### First-Class Package Service rates

Sample shipment from **N.Y.** to **Chicago** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>Walk-in rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td>1-4 oz.</td>
    <td>$3.78</td>
    <td>$2.76</td>
    <td>$2.76</td>
    <td>$2.76</td>
  </tr>
  <tr>
    <td>5-12 oz.</td>
    <Td>$4.53</td>
    <td>$3.28</td>
    <td>$3.28</td>
    <td>$3.28</td>
  </tr>
  <tr>
    <td>13 oz.</td>
    <td>$5.93</td>
    <td>$5.12</td>
    <td>$5.12</td>
    <td>$5.12</td>
  </tr>
  <tr>
    <td>14-15.99 oz.</td>
    <td>Available only online</td>
    <td>$5.12</td>
    <td>$5.12</td>
    <td>$5.12</td>
  </tr>
</table>

### Parcel Select Ground rates

Sample shipment from **N.Y.** to **Chicago** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>Walk-in rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td>Light (1 lbs) </td>
    <td>$7.95</td>
    <td>$7.50</td>
    <td>$7.50</td>
    <td>$7.50</td>
  </tr>
  <tr>
    <td>Medium (3 lbs) </td>
    <td>$11.90</td>
    <td>$9.06</td>
    <td>$9.06</td>
    <td>$9.06</td>
  </tr>
  <tr>
    <td>Heavy (5 lbs) </td>
    <td>$13.14</td>
    <td>$10.13</td>
    <td>$10.13</td>
    <td>$10.13</td>
  </tr>
  <tr>
    <td>Heavier (15 lbs) </td>
    <td>$32.49</td>
    <td>$26.54</td>
    <td>$26.54</td>
    <td>$26.54</td>
  </tr>
</table>

### Media Mail rates

USPS Media Mail only accepts certain items, such as books, music, and other media. Media that contains advertising isn't allowed. For more information, see the <a href="https://pe.usps.com/text/DMM300/273.htm">USPS' approved list for Media Mail.</a></td>

Media Mail rates are based on the weight of the package and not on the destination.

<table>
  <tr>
    <th></th>
    <th>Walk-in rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td>Light (1 lb)</td>
    <td>$2.75</td>
    <td>$2.75</td>
    <td>$2.75</td>
    <td>$2.75</td>
  </tr>
  <tr>
    <td>Medium (3 lbs)</td>
    <Td>$3.79</td>
    <td>$3.79</td>
    <td>$3.79</td>
    <td>$3.79</td>
  </tr>
</table>

<a id="international"></a>
## International shipping with USPS

>Note:
>First Class Mail International was removed on January 21, 2018 due to changes by USPS. Shopify recommends using [First Class Package International](#first-class-package-international-usps-specific) to ship packages that weigh less than 4 pounds. For more information, see the [*USPS guide about these changes*](https://about.usps.com/postal-bulletin/2017/pb22482/html/updt_006.htm).

You can ship internationally using [First Class Package International](#first-class-intl) and [Priority Mail International](#priority-intl) mail types.

<table>
  <tr>
    <th>Shipping Service</th>
    <th>Delivery Timeline</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><a href="https://pe.usps.com/text/imm/immc2_021.htm">First-Class Package International Service</a></td>
    <td>Varies</td>
    <td>An economical way to ship small packages internationally.</td>
  </tr>
  <tr>
    <td><a href="https://www.usps.com/international/priority-mail-international.htm">Priority Mail International</td>
    <td>6-10 business days</td>
    <td>Ship orders internationally to 190 countries.</td>
  </tr>
  <tr>
    <td><a href="https://www.usps.com/international/priority-mail-express-international.htm">Priority Mail Express International</a>*</td>
    <td>3-5 business days</td>
    <td>The fastest way to ship orders internationally to 190 countries.</td>
  </tr>
</table>
\* Guaranteed delivery

<a id="first-class-intl"></a>
### First-Class Package International Service rates

Sample shipment from **N.Y.** to **Toronto** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>Walk-in rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td>Light (1 lbs)</td>
    <td>$17.25</td>
    <td>$15.20</td>
    <td>$15.20</td>
    <td>$15.20</td>
  </tr>
  <tr>
    <td>Medium (3 lbs)</td>
    <td>$26.25</td>
    <td>$23.99</td>
    <td>$23.99</td>
    <td>$23.99</td>
  </tr>
</table>

<a id="priority-intl"></a>
### Priority Mail International rates

Sample shipment from **N.Y.** to **Toronto** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>Walk-in rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td><a href="//store.usps.com/store/browse/uspsProductDetailMultiSkuDropDown.jsp?productId=P_O_FRB1" target="blank">USPS Flat rate box (small)</a></td>
    <Td>$26.85</td>
    <td>$26.18</td>
    <td>$25.84</td>
    <td>$25.50</td>
  </tr>
</table>

## Contact information

If you are using USPS with Shopify Shipping and you need help, you can contact:

<table>
  <tr>
    <th>Situation</th>
    <th>Contact</th>
  </tr>
  <tr>
    <td>Get help before you buy a label.</td>
    <td><a href="https://help.shopify.com/en/questions#/questions">Shopify Support</a></td>
  </tr>
  <tr>
    <td>Get assistance after buying a label, such as rerouting a package.</td>
    <td>1-800-275-8777<br>
    Monday - Friday 8:00 am - 8:30 pm ET<br>
    Saturday 8:00 am - 6:00 pm ET<br>
    TDD/TTY Relay: Call 1-800-877-8339. Ask for 1-800-275-8777.
</td>
  </tr>
  <tr>
    <td>Submit a claim.</td>
    <td><a href="https://www.usps.com/help/claims.htm">USPS claims<br></a> To learn more about submitting a claim to USPS, see, <a href="/manual/shipping/shopify-shipping/shipping-options#insurance-coverage-usps-specific">Submit a claim</a>.</td>
  </tr>
  <tr>
    <td>Dispute a shipping adjustment.</td>
    <td>Send an email to <a href="mailto:VerifyPostageHelp@usps.gov">VerifyPostageHelp@usps.com</a>.</td>
  </tr>
</table>

----

## Domestic shipping with UPS

You can ship domestically using UPS Next Day Air&#174;, UPS Next Day Air Saver&#174;, UPS 2nd Day Air&#174;, UPS 3 Day Select&#174;, and UPS Ground.

<table>
  <tr>
    <th>Shipping Service</th>
    <th>Delivery Timeline</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><a href="https://www.ups.com/us/en/shipping/services/domestic/ground.page?">UPS Ground&#174;</a>*
    </td>
    <td>1-5 business days</td>
    <td>An economical way to ship small packages within the U.S.</td>
  </tr>
  <tr>
    <td><a href="https://www.ups.com/us/en/shipping/services/domestic/3-day-select.page?">UPS 3 Day Select&#174;</a>*</td>
    <td>3 business days</td>
    <td>Ship orders within the U.S.</td>
  </tr>
  <tr>
    <td><a href="https://www.ups.com/us/en/shipping/services/domestic/2nd-day-air.page?">UPS 2nd Day Air&#174;</a>*</td>
    <td>2 business days</td>
    <td>Ship orders quickly within the U.S. that don't require overnight service.</td>
  </tr>
  <tr>
    <td><a href="https://www.ups.com/us/en/shipping/services/domestic/next-day-air-saver.page?">UPS Next Day Air Saver&#174;</a>*</td>
    <td>Next business day (Afternoon)</td>
    <td>Ship orders within the U.S. that need to arrive in the afternoon of the next business day.</td>
  </tr>
  <tr>
    <td><a href="https://www.ups.com/us/en/shipping/services/domestic/next-day-air.page?">UPS Next Day Air&#174;</a>*</td>
    <td>Next business day</td>
    <td>A way to ship orders that need to arrive the next business day.</td>
  </tr>
  <tr>
    <td><a href="https://www.ups.com/us/en/shipping/services/domestic/next-day-air-early.page?">UPS Next Day Air Early&#174;</a>*</td>
    <td>Next business day (Morning)</td>
    <td>Ship orders that need to arrive in the morning of the next business day.</td>
  </tr>
</table>
\* Guaranteed delivery


>Note:
>UPS is limited to shipping from the continental U.S. only. This excludes U.S. territories such as Hawaii, Puerto Rico, and Alaska.

### UPS Next Day Air&#174; rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **N.Y.** to **Chicago** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>List rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
    <tr>
    <td>Light (1 lbs)</td>
    <td>$63.31</td>
    <td>$36.72</td>
    <td>$31.97</td>
    <td>$30.39</td>
  </tr>
  <tr>
    <td>Medium (3 lbs)</td>
    <td>$77.69</td>
    <td>$45.06</td>
    <td>$39.23</td>
    <td>$37.29</td>
  </tr>
  <tr>
    <td>Heavy (5 lbs)</td>
    <td>$85.82</td>
    <td>$49.78</td>
    <td>$43.34</td>
    <td>$41.19</td>
  </tr>
</table>

### UPS Next Day Air Saver&#174; rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **N.Y.** to **Chicago** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>List rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
    <tr>
    <td>Light (1 lbs)</td>
    <td>$56.53</td>
    <td>$32.79</td>
    <td>$28.55</td>
    <td>$27.13</td>
  </tr>
  <tr>
    <td>Medium (3 lbs)</td>
    <td>$69.37</td>
    <td>$40.23</td>
    <td>$35.03</td>
    <td>$33.30</td>
  </tr>
  <tr>
    <td>Heavy (5 lbs)</td>
    <td>$82.58</td>
    <td>$47.90</td>
    <td>$41.70</td>
    <td>$39.64</td>
  </tr>
</table>

### UPS Second Day Air&#174; rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **N.Y.** to **Chicago** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>List rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
    <tr>
    <td>Light (1 lbs)</td>
    <td>$22.66</td>
    <td>$13.14</td>
    <td>$12.12</td>
    <td>$11.56</td>
  </tr>
  <tr>
    <td>Medium (3 lbs)</td>
    <td>$26.94</td>
    <td>$15.63</td>
    <td>$14.41</td>
    <td>$13.74</td>
  </tr>
  <tr>
    <td>Heavy (5 lbs)</td>
    <td>$34.81</td>
    <td>$20.19</td>
    <td>$18.62</td>
    <td>$17.75</td>
  </tr>
</table>

### UPS 3 Day Select&#174; rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **N.Y.** to **Chicago** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>List rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
    <tr>
    <td>Light (1 lbs)</td>
    <td>$16.08</td>
    <td>$11.26</td>
    <td>$11.23</td>
    <td>$11.23</td>
  </tr>
  <tr>
    <td>Medium (3 lbs)</td>
    <td>$19.77</td>
    <td>$13.84</td>
    <td>$13.34</td>
    <td>$12.85</td>
  </tr>
  <tr>
    <td>Heavy (5 lbs)</td>
    <td>$24.21</td>
    <td>$16.95</td>
    <td>$16.34</td>
    <td>$15.74</td>
  </tr>
</table>

### UPS Ground rates

>Note:
>List rates include a $3.60 residential surcharge. The residential surcharge is waived for Shopify merchants.

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **N.Y.** to **Chicago** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>List rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
    <tr>
    <td>Light (1 lbs)</td>
    <td>$9.36</td>
    <td>$8.42</td>
    <td>$8.42</td>
    <td>$8.42</td>
  </tr>
  <tr>
    <td>Medium (3 lbs)</td>
    <td>$11.14</td>
    <td>$10.03</td>
    <td>$10.03</td>
    <td>$10.03</td>
  </tr>
  <tr>
    <td>Heavy (5 lbs)</td>
    <td>$12.27</td>
    <td>$11.04</td>
    <td>$11.04</td>
    <td>$11.04</td>
  </tr>
</table>

## International shipping with UPS

You can ship internationally using UPS Worldwide Express&#174;, UPS Worldwide Saver, UPS World Expedited&#174;, and UPS Standard to Canada.

<table>
  <tr>
    <th>Shipping Service</th>
    <th>Delivery Timeline</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><a href="https://www.ups.com/us/en/shipping/international/services/standard.page?">UPS Standard</a>*</td>
    <td>Day definite by date scheduled</td>
    <td>Ship less-urgent orders to Canada and Mexico only.</td>
    </tr>
    <tr>
      <td><a href="https://www.ups.com/us/en/shipping/international/services/worldwide-expedited.page?">UPS Worldwide Expedited</a>*</td>
      <td>2-5 business days</td>
      <td>Ship less-urgent small packages to 220 countries.</td>
    </tr>
    <tr>
      <td><a href="https://www.ups.com/us/en/shipping/international/services/worldwide-saver.page?">UPS Worldwide Saver</a>*</td>
      <td>1-3 business days (End of Day)</td>
      <td>Ship international orders quickly.</td>
    </tr>
    <tr>
      <td><a href="https://www.ups.com/us/en/shipping/international/services/worldwide-express.page?">UPS Worldwide Express</a>*</td>
      <td>1-3 business days (Morning)</td>
      <td>Ship international orders quickly to 120 countries.</td>
    </tr>
    <tr>
      <td><a href="https://www.ups.com/us/en/shipping/international/services/worldwide-express-plus.page?">UPS Worldwide Express Plus</a>*</td>
      <td>1-3 business days (Early Morning)</td>
      <td>Ship international orders quickly to 55 countries.</td>
    </tr>
</table>
\* Guaranteed delivery

>Note:
>UPS is limited to shipping from the continental U.S. only. This excludes U.S. territories such as Hawaii, Puerto Rico, and Alaska.

### UPS Worldwide Express&#174; rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **N.Y.** to **London** with Shopify Shipping:

<table>
  <tr>
    <th>Weight</th>
    <th>List rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td>Light (1 lbs)</td>
    <td>$102.90</td>
    <td>$55.57</td>
    <td>$48.88</td>
    <td>$46.31</td>
  </tr>
  <tr>
    <td>Medium (3 lbs)</td>
    <td>$136.38</td>
    <td>$73.65</td>
    <td>$64.78</td>
    <td>$61.37</td>
  </tr>
  <tr>
    <td>Heavy (5 lbs)</td>
    <td>$184.89</td>
    <td>$99.84</td>
    <td>$87.82</td>
    <td>$83.20</td>
  </tr>
</table>

### UPS Worldwide Saver rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **N.Y.** to **London** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>List rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
    <tr>
    <td>Light (1 lbs)</td>
    <td>$101.83</td>
    <td>$54.99</td>
    <td>$48.37</td>
    <td>$45.82</td>
  </tr>
  <tr>
    <td>Medium (3 lbs)</td>
    <td>$134.97</td>
    <td>$72.88/td>
    <td>$64.11</td>
    <td>$60.74</td>
  </tr>
  <tr>
    <td>Heavy (5 lbs)</td>
    <td>$183.00</td>
    <td>$98.82</td>
    <td>$86.93</td>
    <td>$82.35</td>
  </tr>
</table>

### UPS World Expedited&#174; rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **N.Y.** to **United Kingdom** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>List rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
    <tr>
    <td>Light (1 lbs)</td>
    <td>$94.29</td>
    <td>$50.92</td>
    <td>$44.79</td>
    <td>$42.43/td>
  </tr>
  <tr>
    <td>Medium (3 lbs)</td>
    <td>$128.22</td>
    <td>$69.24</td>
    <td>$60.90</td>
    <td>$57.70</td>
  </tr>
  <tr>
    <td>Heavy (5 lbs)</td>
    <td>$171.00</td>
    <td>$92.34</td>
    <td>$81.23</td>
    <td>$76.95</td>
  </tr>
</table>

### UPS Standard to Canada rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **N.Y.** to **Toronto** with Shopify Shipping:

<table>
  <tr>
    <th></th>
    <th>List rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
    <tr>
    <td>Light (1 lbs)</td>
    <td>$20.98</td>
    <td>$20.98</td>
    <td>$20.98</td>
    <td>$20.98</td>
  </tr>
  <tr>
    <td>Medium (3 lbs)</td>
    <td>$23.40</td>
    <td>$20.98</td>
    <td>$20.98</td>
    <td>$20.98</td>
  </tr>
  <tr>
    <td>Heavy (5 lbs)</td>
    <td>$26.58</td>
    <td>$23.12</td>
    <td>$22.33</td>
    <td>$21.53</td>
  </tr>
</table>

## Contact information

If you are using UPS with Shopify Shipping and you need help, you can contact:

<table>
  <tr>
    <th>Situation</th>
    <th>Contact</th>
  </tr>
  <tr>
    <td>Get help before you buy a label.</td>
    <td><a href="https://help.shopify.com/en/questions#/questions">Shopify Support</a></td>
  </tr>
  <tr>
    <td>Get assistance after buying a label, such as rerouting a package.</td>
    <td><a href="https://help.shopify.com/en/questions#/questions">Shopify Support</a></td>
  </tr>
  <tr>
    <td>Submit a claim.</td>
    <td>Send an email to <a href="mailto:shipping-support@shopify.com">Shopify Shipping Support</a>. <br>To learn more about submitting a claim for a UPS shipment, see <a href="/manual/shipping/shopify-shipping/shipping-options#submit-a-claim-ups-specific">Submit a claim</a>.</td>
  </tr>
  <tr>
  <td>Dispute a shipping adjustment.</td>
  <td><a href="https://help.shopify.com/en/questions#/questions">Shopify Support</a></td>
  </tr>

</table>

If you purchased a label using your own UPS account and not using Shopify Shipping, you need to contact UPS directly:

**UPS Support (US)**

Domestic orders: 1-800-742-5877

International orders: 1-800-782-7892

TDD/TTY: 1-800-833-0056

----

## International rates with DHL Express

You can ship internationally with DHL Express Worldwide.

<table>
  <tr>
    <th>Shipping Service</th>
    <th>Delivery Timeline</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>DHL Express Worldwide *</td>
    <td>2-5 business days</td>
    <td>Ship time-sensitive international orders to 220 countries.</td>
  </tr>
</table>
\* Guaranteed delivery

>Note:
>DHL Express is limited to shipping from the continental U.S. only. This excludes U.S. territories such as Hawaii, Puerto Rico, and Alaska.

### DHL Express Worldwide rates

The example rates below don't include taxes or fuel surcharges.

>Note:
>DHL Express doesn't provide shipping to Russia.

<table>
<tr>
  <th>Destination</th>
  <th>Weight</th>
  <th>List rate</th>
  <th>Basic Shopify plan</th>
  <th>Shopify plan</th>
  <th>Advanced Shopify plan</th>
</tr>
<tr>
  <td rowspan="3">Canada</td>
  <td>Light (1 lbs)</td>
  <td>$77.78</td>
  <td>$40.55</td>
  <td>$28.54</td>
  <td>$26.28</td>
</tr>
<tr>
  <td>Medium (3 lbs)</td>
  <td>$95.69</td>
  <td>$48.26</td>
  <td>$33.96</td>
  <td>$31.28</td>
</tr>
<tr>
  <td>Heavy (5 lbs)</td>
  <td>$113.61</td>
  <td>$59.61</td>
  <td>$41.95</td>
  <td>$38.63</td>
</tr>
<tr>
  <td rowspan="3">London</td>
  <td>Light (1 lbs)</td>
  <td>$100.24</td>
  <td>$48.74</td>
  <td>$34.30</td>
  <td>$31.59</td>
</tr>
<tr>
  <td>Medium (3 lbs)</td>
  <td>$136.15</td>
  <td>$65.10</td>
  <td>$48.81</td>
  <td>$42.19</td>
</tr>
<tr>
  <td>Heavy (5 lbs)</td>
  <td>$178.27</td>
  <td>$86.22</td>
  <td>$60.68</td>
  <td>$55.88</td>
</tr>
<tr>
  <td rowspan="3">Australia</td>
  <td>Light (1 lbs)</td>
  <td>$108.02</td>
  <td>$53.96</td>
  <td>$37.97</td>
  <td>$34.98</td>
</tr>
<tr>
  <td>Medium (3 lbs)</td>
  <td>$147.15</td>
  <td>$76.05</td>
  <td>$53.52</td>
  <td>$49.29</td>
</tr>
<tr>
  <td>Heavy (5 lbs)</td>
  <td>$182.67</td>
  <td>$101.32</td>
  <td>$71.30</td>
  <td>$65.67</td>
</tr>
<tr>
  <td rowspan="3">Hong Kong SAR China</td>
  <td>Light (1 lbs)</td>
  <td>$90.93</td>
  <td>$51.98</td>
  <td>$36.58</td>
  <td>$33.69</td>
</tr>
<tr>
  <td>Medium (3 lbs)</td>
  <td>$125.75</td>
  <td>$72.07</td>
  <td>$50.72</td>
  <td>$46.72</td>
</tr>
<tr>
  <td>Heavy (5 lbs)</td>
  <td>$159.04</td>
  <td>$90.52</td>
  <td>$63.70</td>
  <td>$58.67</td>
</tr>
</table>

>Note:
>There is an added surcharge if your delivery destination is in a remote area. Check if your destination post/zip code is considered remote in DHL's [Remote Area List 2017](http://www.dhl.com/content/dam/downloads/g0/express/services/surcharges/dhl_express_remote_areas.pdf).

## Contact information

If you are using DHL Express with Shopify Shipping and you need help, you can contact:

<table>
  <tr>
    <th>Situation</th>
    <th>Contact</th>
  </tr>
  <tr>
    <td>Get help before you buy a label.</td>
    <td><a href="https://help.shopify.com/en/questions#/questions">Shopify Support</a></td>
  </tr>
  <tr>
    <td>Get assistance after buying a label, such as rerouting a package.</td>
    <td><a href="https://help.shopify.com/en/questions#/questions">Shopify Support</a></td>
  </tr>
  <td>Submit a claim.</td>
  <td>Send an email to <a href="mailto:shipping-support@shopify.com">Shopify Shipping Support</a>. <br>To learn more about submitting a claim for a DHL Express shipment, see <a href="/manual/shipping/shopify-shipping/shipping-options#submit-a-claim-dhl-express-specific">Submit a claim</a>.</td>
</tr>
  <tr>
    <td>Dispute a shipping adjustment.</td>
    <td><a href="https://help.shopify.com/en/questions#/questions">Shopify Support</a></td>
  </tr>
</table>

----

## Domestic shipping with Canada Post

You can ship domestically using [Expedited Parcel](#expedited-parcel-rates), [Xpresspost](#-rates), and [Priority](#priority-rates) mail types.

<table>
  <tr>
    <th>Shipping Service</th>
    <th>Delivery Timeline</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><a href="https://www.canadapost.ca/cpc/en/business/shipping/canada/compare/expedited.page?">Expedited Parcel</a></td>
    <td>1-7 business days</td>
    <td>An economical way to ship packages within Canada. </td>
  </tr>
  <tr>
    <td><a href="https://www.canadapost.ca/cpc/en/business/shipping/canada/compare/xpresspost.page?">Xpresspost</a></td>
    <td>1-2 business days</td>
    <td>Ship documents and parcels quickly within Canada.</td>
  </tr>
  <tr>
    <td><a href="https://www.canadapost.ca/cpc/en/business/shipping/canada/compare/priority.page?#!navtabd6518e6">Priority</a></td>
    <td>Next business day</td>
    <td>Canada Post's fastest domestic delivery for time-sensitive documents and parcels.</td>
  </tr>
</table>

>Note:
>Shopify Shipping doesn't offer Regular Parcel rates. The Expedited Parcel rates cost less and deliver faster with Shopify Shipping.

### Expedited Parcel rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **Toronto** to **Calgary** with Shopify Shipping:

>Note:
>The example rates below are listed in CAD.

<table>
  <tr>
    <th></th>
    <th>2018 retail rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td>Very Light (0.5 kg)</td>
    <td>$14.66</td>
    <td>$13.50</td>
    <td>$12.99</td>
    <td>$12.54</td>
  </tr>
  <tr>
    <td>Light (1.0 kg)</td>
    <td>$15.59</td>
    <td>$14.26</td>
    <td>$13.68</td>
    <td>$13.11</td>
  </tr>
  <tr>
    <td>Medium (3 kg)</td>
    <td>$19.14</td>
    <td>$17.57</td>
    <td>$16.88</td>
    <td>$16.20</td>
  </tr>
  <tr>
    <td>Heavy (5 kg)</td>
    <td>$22.32</td>
    <td>$20.55</td>
    <td>$19.74</td>
    <td>$19.01</td>
  </tr>
</table>

### Xpresspost rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **Toronto** to **Calgary** with Shopify Shipping:

>Note:
>The example rates below are listed in CAD.

<table>
  <tr>
    <th></th>
    <th>2018 retail rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td>Very Light (0.5 kg)</td>
    <td>$16.37</td>
    <td>$15.25</td>
    <td>$14.89</td>
    <td>$14.60</td>
  </tr>
  <tr>
    <td>Light (1.0 kg)</td>
    <td>$21.68</td>
    <td>$20.18</td>
    <td>$19.80</td>
    <td>$19.55</td>
  </tr>
  <tr>
    <td>Medium (3 kg)</td>
    <td>$39.93</td>
    <td>$37.41</td>
    <td>$36.84</td>
    <td>$36.22</td>
  </tr>
  <tr>
    <td>Heavy (5 kg)</td>
    <td>$50.91</td>
    <td>$47.78</td>
    <td>$47.21</td>
    <td>$46.56</td>
  </tr>
</table>

### Priority rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **Toronto** to **Calgary** with Shopify Shipping:

>Note:
>The example rates below are listed in CAD.

<table>
  <tr>
    <th></th>
    <th>2018 retail rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td>Very Light (0.5 kg)</td>
    <td>$41.77</td>
    <td>$39.26</td>
    <td>$38.57</td>
    <td>$37.86</td>
  </tr>
  <tr>
    <td>Light (1.0 kg)</td>
    <td>$42.65</td>
    <td>$39.79</td>
    <td>$39.10</td>
    <td>$38.38</td>
  </tr>
  <tr>
    <td>Medium (3 kg)</td>
    <td>$57.21</td>
    <td>$53.37</td>
    <td>$52.22</td>
    <td>$51.08</td>
  </tr>
  <tr>
    <td>Heavy (5 kg)</td>
    <td>$70.79</td>
    <td>$65.92</td>
    <td>$64.32</td>
    <td>$62.86</td>
  </tr>
</table>

## USA shipping with Canada Post

Canada Post offers a range of different options for shipping to the United States, including [Xpresspost USA](#xpresspost-usa-rates) and [Expedited Parcel USA](#expedited-parcel-usa-rates).

<table>
  <tr>
    <th>Shipping Service</th>
    <th>Delivery Timeline</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><a href="https://www.canadapost.ca/cpc/en/business/shipping/international/compare/small-packet-usa.page?">Small Packet&trade; USA - Air</td>
    <td>5-8 business days</td>
    <td>An economical way to ship small and lightweight (under 1 kg) packages to the U.S.</td>
  </tr>
  <tr>
    <td><a href="https://www.canadapost.ca/cpc/en/business/shipping/international/compare/tracked-packet-usa.page?">Tracked Packet&trade; - USA</a></td>
    <td>4-7 business days</td>
    <td>Ship small and lightweight (under 1 kg) items faster to the U.S.</td>
  </tr>
  <tr>
    <td><a href="https://www.canadapost.ca/cpc/en/business/shipping/international/compare/expedited-parcel-usa.page?">Expedited Parcel&trade; - USA</a></td>
    <td>4-7 business days</td>
    <td>Ship bigger and heavier (under 30 kg) parcels to the U.S.</td>
  </tr>
  <tr>
    <td><a href="https://www.canadapost.ca/cpc/en/business/shipping/international/compare/xpresspost-usa.page?">Xpresspost&trade; - USA</a></td>
    <td>2-3 business days</td>
    <td>Canada Post's fastest option for shipping orders to the U.S.</td>
  </tr>
</table>

### Xpresspost USA rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **Toronto** to **New York** with Shopify Shipping:

>Note:
>The example rates below are listed in CAD.

<table>
  <tr>
    <th></th>
    <th>2018 retail rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td>Very Light (0.5 kg)</td>
    <td>$30.25</td>
    <td>$28.16</td>
    <td>$27.39</td>
    <td>$26.84</td>
  </tr>
  <tr>
    <td>Light (1.0 kg)</td>
    <td>$32.64</td>
    <td>$30.63</td>
    <td>$29.48</td>
    <td>$29.10</td>
  </tr>
  <tr>
    <td>Medium (3 kg)</td>
    <td>$39.80</td>
    <td>$37.28</td>
    <td>$37.06</td>
    <td>$36.54</td>
  </tr>
  <tr>
    <td>Heavy (5 kg)</td>
    <td>$51.29</td>
    <td>$48.07</td>
    <td>$44.89</td>
    <td>$44.74</td>
  </tr>
</table>

### Expedited Parcel USA rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **Toronto** to **New York** with Shopify Shipping:

>Note:
>The example rates below are listed in CAD.

<table>
  <tr>
    <th></th>
    <th>2018 retail rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td>Very Light (0.5 kg)</td>
    <td>$19.72</td>
    <td>$18.53</td>
    <td>$18.26</td>
    <td>$18.17</td>
  </tr>
  <tr>
    <td>Light (1.0 kg)</td>
    <td>$21.44</td>
    <td>$20.20</td>
    <td>$19.58</td>
    <td>$19.22</td>
  </tr>
  <tr>
    <td>Medium (3 kg)</td>
    <td>$26.75</td>
    <td>$25.21</td>
    <td>$24.74</td>
    <td>$24.68</td>
  </tr>
  <tr>
    <td>Heavy (5 kg)</td>
    <td>$32.11</td>
    <td>$29.89</td>
    <td>$29.48</td>
    <td>$29.42</td>
  </tr>
</table>

>Note:
>Shopify Shipping doesn't offer Priority Worldwide rates to the United States.

## International rates with Canada Post

Canada Post offers [Xpresspost International](#xpresspost-international-rates) for international shipping.

<table>
  <tr>
    <th>Shipping Service</th>
    <th>Delivery Timeline</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><a href="https://www.canadapost.ca/cpc/en/business/shipping/international/compare/small-packet-international.page?">Small Packet&trade; International - Surface or Air</a></td>
    <td>
      Air: 6-10 business days
      Surface: 1-3 months
    </td>
    <td>An economical way to ship less-urgent small and lightweight (under 2 kg) items internationally.</td>
  </tr>
  <tr>
    <td><a href="https://www.canadapost.ca/cpc/en/business/shipping/international/compare/international-parcel.page?">International Parcel&trade; - Surface or Air</a></td>
    <td>
      Air: 12+ business days
      Surface: 1-3 months
    </td>
    <td>An economical way to ship less-urgent large and heavy items internationally. Ship to countries that don't offer Xpresspost - International.</td>
  </tr>
  <tr>
    <td><a href="https://www.canadapost.ca/cpc/en/business/shipping/international/compare/tracked-packet-international.page?">Tracked Packet&trade; - International</a></td>
    <td>6-10 business days</td>
    <td>A way to ship small and lightweight (under 2 kg) items to 31 countries.</td>
  </tr>
  <tr>
    <td><a href="https://www.canadapost.ca/cpc/en/business/shipping/international/compare/xpresspost-international.page?">Xpresspost&trade; - International</a></td>
    <td>4-7 business days</td>
    <td>Canada Post's fastest shipping option to 70+ countries.</td>
  </tr>
</table>

>Note:
>Shopify Shipping doesn't offer Priority Worldwide shipping rates internationally.

### Xpresspost International rates

The example rates below don't include taxes or fuel surcharges.

Sample shipment from **Toronto** to **London** with Shopify Shipping:

>Note:
>The example rates below are listed in CAD.


<table>
  <tr>
    <th></th>
    <th>2018 retail rate</th>
    <th>Basic Shopify plan</th>
    <th>Shopify plan</th>
    <th>Advanced Shopify plan</th>
  </tr>
  <tr>
    <td>Very Light (0.5 kg)</td>
    <td>$65.06</td>
    <td>$60.56</td>
    <td>$51.27</td>
    <td>$50.17</td>
  </tr>
  <tr>
    <td>Light (1.0 kg)</td>
    <td>$72.81</td>
    <td>$67.86</td>
    <td>$62.40</td>
    <td>$57.05</td>
  </tr>
  <tr>
    <td>Medium (3 kg)</td>
    <td>$105.01</td>
    <td>$97.70</td>
    <td>$89.09</td>
    <td>$83.78</td>
  </tr>
  <tr>
    <td>Heavy (5 kg)</td>
    <td>$147.27</td>
    <td>$133.78</td>
    <td>$120.75</td>
    <td>$112.90</td>
  </tr>
</table>

>Information:
>You can learn more about the pricing and availability of Canada Post's mail types using the [2018 Parcel Services Commercial Price Guide](//www.canadapost.ca/tools/pg/prices/SBParcels-e.pdf).

## Contact information

If you are using Canada Post with Shopify Shipping and you need help, you can contact:

<table>
  <tr>
    <th>Situation</th>
    <th>Contact</th>
  </tr>
  <tr>
    <td>Get help before you buy a label.</td>
    <td><a href="https://help.shopify.com/en/questions#/questions">Shopify Support</a></td>
  </tr>
  <tr>
    <td>Get assistance after buying a label, such as rerouting a package.</td>
    <td><a href="https://help.shopify.com/en/questions#/questions">Shopify Support</a></td>
  </tr>
  <tr>
    <td>Submit a claim.</td>
    <td><a href="https://www.canadapost.ca/cpotools/apps/ccm/business/claim?execution=e1s1
">Canada Post claims
</a></td>
  </tr>
  <tr>
    <td>Dispute a shipping adjustment.</td>
    <td><a href="https://www.canadapost.ca/web/en/pages/support/default.page#panel2-3
">Canada Post Support
</a></td>
  </tr>
</table>
