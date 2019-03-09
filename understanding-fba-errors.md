---
description: >-
  This page list the description of all the possible FBA errors to help you
  understand the issue.
---

# Understanding FBA Errors

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Message</b>
      </th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">ITEM_EXCLUDED_FROM_COMMINGLING_FOR_EXISTING_MAP</td>
      <td style="text-align:left">Not all products are eligible for Stickerless Commingled Inventory. Most
        notably in grocery, health and beauty, and media products must always be
        labeled. <b>Amazon is always  evaluating categories and products and may change the eligibility for products at any  time. </b>
        <br
        />Possible solution: Add the item to the FBA Shipment in <em><b>SellerCentral.</b></em> After
        adding the item the following message may be returned (along these lines):
        This product is not eligible for stickerless, commingling<b> This product requires labeling to be received at our fulfillment centers.</b>  <b>I agree to apply labels to these products. </b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">ITEM_WITH_NO_VALID_FC</td>
      <td style="text-align:left">Item has no eligible Fulfillment Center as it is hazmat (hazardous material)
        so you can not send to FBA.</td>
    </tr>
    <tr>
      <td style="text-align:left">NO_EXTERNAL_IDENTIFIER_FOR_EXISTING_MAP</td>
      <td style="text-align:left">Product is missing the UPC on Seller Central.</td>
    </tr>
    <tr>
      <td style="text-align:left">Failed to preview package reason= PARENT_IAID</td>
      <td style="text-align:left">A matrix parent is included in the inbound shipment. Only matrix children
        can be sent. (The matrix parent SKU is not a real item)</td>
    </tr>
    <tr>
      <td style="text-align:left">UNKNOWN_SKU</td>
      <td style="text-align:left">This SKU is not in your FBA Catalog.
        <br /> <b>Solution</b>: Change the product to Fulfilled by Amazon. Launch to
        Amazon and wait a few minutes. Then retrieve the FNSKU by executing the
        action Get FNSKU.</td>
    </tr>
    <tr>
      <td style="text-align:left">ITEM_UNDER_HAZMAT_REVIEW</td>
      <td style="text-align:left">Potential Hazardous Material (Hazmat). Product under review by Amazon.
        The product will not be accepted until we have completed our review and
        determined it meets Amazon&apos;s product compliance standards. This process
        generally takes between 4-7 business days. This item must be removed</td>
    </tr>
    <tr>
      <td style="text-align:left">You must include a valid ShipmentId with a call to the CreateInboundShipment
        operation. Get ShipmentId values by calling the CreateInboundShipmentPlan
        operation. The request to CreateInboundShipment must include only items
        and quantities that have been previously planned through CreateInboundShipmentPlan</td>
      <td
      style="text-align:left">The temporary ID assigned to a previewed shipment expires after 48 hours.</td>
    </tr>
    <tr>
      <td style="text-align:left">Insufficient inventory capacity for the operation</td>
      <td style="text-align:left"><b>From Amazon Seller Forums</b> - You may have an inventory storage limit.
        Inventory storage limits generally apply to new FBA sellers and existing
        FBA sellers with slower-turning inventory.
        <br />If your Amazon FBA account is configured for Unlimited storage:
        <br />One of the items in the Preview have an ASIN level capacity restriction.
        <br
        />Unfortunately, Amazon does not tell us which item is causing the error.</td>
    </tr>
    <tr>
      <td style="text-align:left">MISSING_DIMENSIONS</td>
      <td style="text-align:left">
        <p></p>
        <p>Product is missing dimensions for FBA.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">EXTERNAL_ID_MAPS_MULTIPLE_IAIDS</td>
      <td style="text-align:left">UPC for the listing was assigned to multiple ASINs. Hence, when you are
        sending the shipment, the ASINs are conflicting at the back end and causing
        errors to the system. Can happen when an item that used to be stickerless
        now becomes requiring label, because the UPC associated with this ASIN
        used to be associated with that ASIN only, but now associated with more
        than one ASIN. Solution - You may need to create a new listing on Seller
        Central.</td>
    </tr>
    <tr>
      <td style="text-align:left">Shipping Status is ERROR_ESTIMATING</td>
      <td style="text-align:left">There&apos;s an error in the address. For example, the zip code is invalid
        because of a period at the end of the zip code.</td>
    </tr>
    <tr>
      <td style="text-align:left">Shipping Status is ERROR_ESTIMATING</td>
      <td style="text-align:left">There&apos;s an error in the address. For example, the zip code is invalid
        because of a period at the end of the zip code.</td>
    </tr>
    <tr>
      <td style="text-align:left">AmazonContractNotSigned</td>
      <td style="text-align:left">Seller has not accepted Amazon&#x2019;s Partnered Carrier Program terms
        and conditions. Seller should accept Amazon&#x2019;s Partnered Carrier
        Program terms and conditions on <a href="https://sellercentral.amazon.co.uk/gp/help/201119120">Seller Central</a>.</td>
    </tr>
    <tr>
      <td style="text-align:left">CannotConfirmTransportContent</td>
      <td style="text-align:left">The Amazon-partnered shipment request is ineligible for confirmation.
        Check if the shipment is already confirmed.</td>
    </tr>
    <tr>
      <td style="text-align:left">CannotEstimateTransportContent</td>
      <td style="text-align:left">The Amazon-partnered shipment request is ineligible for estimation. Ensure
        that the <b>ShipFrom  </b>address is in a marketplace that is eligible for
        Amazon&apos;s Partnered Carrier Program.</td>
    </tr>
    <tr>
      <td style="text-align:left">CannotVoidTransportContent</td>
      <td style="text-align:left">The Amazon-partnered shipment request can no longer be voided.</td>
    </tr>
    <tr>
      <td style="text-align:left">CarrierContractNotSigned</td>
      <td style="text-align:left">Seller has not accepted the carrier&#x2019;s terms and conditions. Seller
        should accept the carrier&#x2019;s existing or revised terms and conditions
        on <a href="https://sellercentral.amazon.co.uk/gp/help/201119120">Seller Central</a>.</td>
    </tr>
    <tr>
      <td style="text-align:left">CarrierInvalidForMarketplace</td>
      <td style="text-align:left">The specified carrier is not supported in the marketplace where the inbound
        shipment originates.</td>
    </tr>
    <tr>
      <td style="text-align:left">InvalidCountrySubdivisionCode</td>
      <td style="text-align:left">The specified <b>ShipToCountrySubdivisionCode</b>is invalid. Ensure that
        the <b>ShipToCountrySubdivisionCode</b>value is for a country subdivision
        that contains an Amazon fulfillment center that the seller is registered
        with.</td>
    </tr>
    <tr>
      <td style="text-align:left">MissingCarrierType</td>
      <td style="text-align:left">No <b>CarrierName </b>value was specified. Specify a valid <b>CarrierName </b>value.</td>
    </tr>
    <tr>
      <td style="text-align:left">NoPackagesOrPallets</td>
      <td style="text-align:left">No package information (for Small Parcel shipments) or pallet information
        (for Less Than Truckload/Full Truckload (LTL/FTL) shipments) was specified.
        Specify this information using either the <b>PackageList </b>or the <b>PalletListparameter </b>of
        the PutTransportContent operation.</td>
    </tr>
    <tr>
      <td style="text-align:left">TransportContentNotFound</td>
      <td style="text-align:left">No Amazon-partnered shipment was associated with the specified <b>ShipmentId </b>value.
        Specify a <b>ShipmentId </b>value that is associated with an Amazon-partnered
        shipment.</td>
    </tr>
    <tr>
      <td style="text-align:left">UnknownCarrierType</td>
      <td style="text-align:left">No carrier was found that matched the specified <b>CarrierName </b>value.
        Specify a valid <b>CarrierName </b>value.</td>
    </tr>
    <tr>
      <td style="text-align:left">Unexpected Error occurred &lt;Code&gt;<b>500</b>&lt;Code&gt;</td>
      <td style="text-align:left">An HTTP 500 error does usually indicate its an Amazon server issues, and
        by waiting 30 mins to an hour the issue should be resolved.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>EXP_DATED_ITEM_HAS_EXISTING_STICKERLESS_MAP</b>
      </td>
      <td style="text-align:left">e merchant&apos;s SKU is marked as a commingled product but it&apos;s
        actually not commingable.
        <br />Amazon might change that error message to: <b>Expiry-dated or lot-controlled product  cannot be commingled. Please create new listing for the same ASIN but different SKU.</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">LABEL_PREP_OWNER_INCOMPATIBILITY_ERROR</td>
      <td style="text-align:left">Can occur when AMAZON_LABEL_ONLY is being sent. amazon is returning a
        message that they do not have enough information about the product to label
        the product themselves. For example, if the product does not have a UPC.
        <br
        /> <b>Solution</b>: either add the product information, or label items yourself.
        Use the Seller Label option.</td>
    </tr>
    <tr>
      <td style="text-align:left">Over_ASIN_Guidance</td>
      <td style="text-align:left">FBA guides sellers to align their inventory supply with buyer demand,
        and they check if there are sufficient inventory capacities for the given
        items. You are already at the maximum inventory allowed for this product,
        due to capacity or other restrictions.
        <br /> <b>Solution:</b> Item must be removed from your batch to finish creating
        your shipment</td>
    </tr>
    <tr>
      <td style="text-align:left">Seller is blocked by the AndonCordManager.</td>
      <td style="text-align:left">You have probably been stopped by an FBA compliance issue. Check your
        account health and speak to an Amazon rep if possible.</td>
    </tr>
    <tr>
      <td style="text-align:left">SupplyCategoryUnavailable</td>
      <td style="text-align:left">
        <p>ASIN is enrolled in UNO (Small &amp; Light) program and MCF cannot fulfill
          UNO ASINs.</p>
        <p>Small and Light can be used only to fulfill Amazon orders.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">EXTERNAL_ID_MAPS_MULTIPLE_IAIDS_FOR_EXISTING_MAP</td>
      <td style="text-align:left">The item has a new FNSKU and can longer be posted under the exising one.</td>
    </tr>
  </tbody>
</table>