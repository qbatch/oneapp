# Ship Products To Amazon \(FBA\)

## STEP 1: CREATE BATCH {#step1}

Here's a line for us to start with. Batch

### Products not in Seller’s Catalog:

1. Search a product using Title, ASIN, UPC, EAN or ISBN on List/Ship → Search Product page.
2. Click on Add to Batch button to add a product in an OPEN or DRAFT batch.
3. Seller can manually add a SKU or generate a new sku using the button Generate MSKU.
4. Similarly you can add in your Product Cost Price/List Price and required Quantity to ship.
5. Seller can add in Minimum/Maximum Sell Price for a repricer at the time of adding a product, similarly he can choose the reprice strategy to be applied to this product, reprice can be enabled for this product right away using the Reprice toggle button on this form, which would only be enabled if min, max price and strategy is selected.
6. Seller can choose from the dropdown if he wants to add a product to a DRAFT \(default\) or OPEN batch.

> ```
> Before shipping a product to Amazon, it is must to list product in seller’s catalog.
> If seller wants to list a product using a different SKU he also has to choose this process.
> ```

### Products Exist in Seller’s Catalog:
#### Add Single Product to Batch:

1. Search a product using Title, ASIN, UPC, EAN or ISBN on List/Ship → Search Product page.
2. Click on Add to Batch button to add a product in an DRAFT or OPEN batch.
3. By default first Amazon fulfilled product exists in a catalog would be selected with a condition and SKU, seller can choose from a list if it has multiple products with that ASIN, Form would be auto filled with last used values for this product.
4. Similarly you can add in your Product Cost Price/List Price and required Quantity to ship.
5. Seller can add in Minimum/Maximum Sell Price for a repricer at the time of adding a product, similarly he can choose the reprice strategy to be applied to this product, reprice can be enabled for this product right away using the Reprice toggle button on this form, which would only be enabled if min, max price and strategy is selected.
6. Seller can choose from the dropdown if he wants to add a product to a DRAFT or OPEN batch.

#### Add Multiple Products to Batch:

1. Go to Inventory → List Page, find products using custom filters, Seller can select multiple products using checkbox, selected products would be preserved while you can change filters and select other products for the batch. You can view selected products anytime using the View Selected option, and clear selection using Clear Selection option.
2. Seller can choose from the Add To Batch dropdown if he wants to add a product to a DRAFT or OPEN batch.

## STEP 2: WORK ON BATCH {#step2}

Here's a line for us to start with  
1. Go to List/Ship → Batches page to finalize your OPEN/DRAFT batch.  
2. To finalize click on WORK button to continue to Create Shipment Plan page.

> ```
> By default batch privacy would be OPEN to every user, which means any user can add items to this batch, if it is LOCKED only a user who has created can add items
> ```

3. User can edit the batch name, select the batch privacy, ship from warehouse, package and label types for a particular batch.
4. Seller can manually enter/update any field directly or use the Add Details to Selected button to bulk edit the Cost Price, Minimum price, Maximum price or Quantity.

> ```
> Product Catalog Status (hover on status for details)
> EXIST: Product Already exist in seller’s catalog
> PENDING: Adding a new product to catalog is in progress
> ERROR: A Product cannot be added to seller’s catalog because of any error, you cannot go to next step without removing this product from the batch.
> ```

5. You can press Create Shipment Plan button to proceed, in case of errors you can see the errors on screen and you need to fix
   any errors mentioned.


## STEP 3: FINALISE BATCH {#step3}

Here's a line for us to start with.  
1. A shipment plan would suggest to create multiple shipments recommended by Amazon based on Fulfilment center and Label Type. App would show any existing shipments for the same Fulfillment Center and Label type next to a shipment recommended by amazon so that can be merged. If you want to merge with an existing shipment you can mark the checkbox otherwise a new shipment would be created. A recommended shipment can be removed using a \(x\) button at the end of row.  
2. You can also select the Box Content Source for the newly created shipments from the top menu, you can choose between `NONE` \(default\), `2D\_Barcode` and `FEED`.  
3. You can press Create Shipments to proceed, you would be taken to shipments page where you can view the shipments created by this particular  batch.

## STEP 4: PACK BATCH {#step4}

Here's a line for us to start with.This is [an example](http://example.com/ "Title") inline link with a title.

1. You would be redirected to List/Ship → Shipments page to finalise a shipment.
2. You can Edit/Update/Remove and print Shipping Labels for any shipment.
3. Click on ITEMS button to View/Pack shipment items into boxes.
4. Select the items using the checkbox, you can add a custom quantity to a box by editing the Qty to Box field, click on the Add to Box button to add items into an existing box or create a new box.
5. Item quantity in a box can be edited in the box and you are also able to add a custom expiry date to a product.
6. A product can be removed from a box using delete button, Item label can be printed using the print button.
7. Shipment Item List shows the number of products in a particular box and the remaining quantity to be packed.
8. When All items are successfully packed to boxed you can submit a feed using a Submit Feed button on the top.



## Compete With Buy Box {#1}
We allow users to compete with Buy Box offer. Users are able to add/subtract to/from Buy Box price.  In this rule, users may choose one option either Subtract From Buy Box Price or Add To Buy Box Price. Users can enter price and select the price to plus/minus in % or $. According to this rule, Repricer will find the Buy Box offer and apply the strategy.
Note:  Buy Box we compete to can be FBM, FBA or Amazon.
If user sets a rule that subtract/add from/to Buy Box price and apply this rule on a product and enable repricing for it. Repricer will reprice accordingly.
What if Buy Box price found less than product's minimum price or greater than maximum price or there is a possibility that there is no Buy Box offer or you are already in a Buy Box. In this case users can set rules for these scenarios in strategy.


### Scenarios:

#### When Buy Box Below Your Minimum Price:
We allow users to select one of the following options in this case:
`Use Maximum`:  It will set price to Maximum Price.
`Use Minimum`:  It will set price to Minimum Price.
`Next Lowest`: Repricer will find the rating best price above your Minimum Price and add/subtract according to rule from it and sets a new price. This option is also applicable if products have no Buy Box offer.
Don't Reprice:  It will not re-price.

#### When Buy Box Above Maximum:
We allow users to select one of the following options in this case:
`Use Maximum`: It will set price to Maximum Price.
`Use Minimum`: It will set price to Minimum Price.
`Don't Reprice`: It will not re-price.

#### When You Are Buy Box Winner:
We allow users to select one of the following options in this case:
Decrease By Competition: Repricer will find the best price above our price so we may not lose our Buy Box and stay in a competitive price. Users can enter price and select the price to add/minus in % or $. Repricer will reprice it accordingly.
Don't Reprice: In this case, When you are in Buy Box, Repricer will not re-price.



##Compete With Lowest Price: {#2}
We allow users to compete with Lowest offer. Users are able to add/subtract from/to Lowest price. In this rule, users may choose one option either Subtract From Lowest Price or Add To Lowest Price. Users can enter price and select the price to add/minus in % or $. According to this rule, Repricer will find the Lowest offer price and apply the strategy.
If user sets a rule that subtract/add from/to Lowest price and apply this rule on a product and enable repricing for it. Reprice will re-price accordingly.
What if Lowest price found less than product's minimum price or equal minimum price. In this case we allow users to set rules in the strategy.


### Scenarios:
#### When Lowest Price Below Minimum:
If Repricer found Lowest Price below your Minimum Price and user selects one of the following options.
`Use Maximum`: It will set price to Maximum Price.
`Use Minimum`: It will set price to Minimum Price.
`Next Lowest`: Repricer will find the rating best price above your Minimum Price and add/subtract according to rule from it and sets a new price.
`Don't Reprice`:  It will not re-price.

#### When Lowest Price equals Minimum:
If  Repricer found Lowest Price equals your Minimum Price and user selects one of the following options:
`Use Maximum`: It will set price to Maximum Price.
`Use Minimum`: It will set price to Minimum Price.
`Don't Reprice`: It will not re-price.

#### If No Competition:
If our Re pricer found no competition and users select one of the following options:
`Use Maximum`: It will set price to Maximum Price.
`Use Minimum`: It will set price to Minimum Price.
`Don't Reprice`: It will not re-price.


## Exclude Sellers {#3}
User can exclude sellers while competing to other offers. Users can select following options to exclude sellers:
Ignore Seller Rating: User can enter Seller Rating and Feedback count to exclude sellers. Repricer will not compete with the Feedback Rating and Count less than and equal to the number that user enters.
`Ignore Seller Ids`: User can enter multiple Seller Ids to exclude them from competing with. Repricer will not compete with them.
`Ignore If Seller is Fulfilled By Merchant`: User can select this option to exclude FBM sellers.
`Ignore If seller is Amazon`: User can select this option to exclude Amazon selling offer.
`Ignore If seller with free shipping`: User can select this option to exclude sellers with free shipping.
