## Repricing[Buy Box Winner Already](/REPRICER.md#6) Mode: {#1}

Our repricer has two modes. Live Mode and Test Mode. In Test Mode our repricer will reprice the products and display prices within our system in reprice suggestions page, where users can see change prices and confirm whether they want to upload them to Amazon or not. With Test Mode, you can try out our Repricer.  
In Live Mode, We will upload these price changes directly to Amazon and we display all the price changes to Amazon within our system in reprice history page.

## Enable/Disable Repricer: {#1}

We have settings page where we allow users to enable/disable the repricer. When user clicks on enable button, Our repricer will  
be able to receive notifications for that user and start repricing. On the other hand, when user clicks on disable button, Our repricer will not reprice[^2] the products price for that user. For products repricing users must enable the repricer.

## Compete With Buy Box {#1}

We allow users to compete with Buy Box offer. Users are able to add/subtract to/from Buy Box price.  In this rule, users may choose one option either Subtract From Buy Box Price or Add To Buy Box Price. Users can enter price and select the price to plus/minus in % or $. According to this rule, Repricer will find the Buy Box offer and apply the strategy.  
Note:  Buy Box we compete to can be FBM, FBA or Amazon.  
If user sets a rule that subtract/add from/to Buy Box price and apply this rule on a product and enable repricing for it. Repricer will reprice accordingly.  
What if Buy Box price found less than product's minimum price or greater than maximum price or there is a possibility that there is no Buy Box offer or you are already in a Buy Box. In this case users can set rules for these scenarios in strategy.

### Scenarios:

#### When Buy Box Below Your Minimum Price: {#4}

We allow users to select one of the following options in this case:  
`Use Maximum`:  It will set price to Maximum Price.  
`Use Minimum`:  It will set price to Minimum Price.  
`Next Lowest`: Repricer will find the rating best price above your Minimum Price and add/subtract according to rule from it and sets a new price. This option is also applicable if products have no Buy Box offer.  
Don't Reprice:  It will not re-price.

#### When Buy Box Above Maximum Price: {#5}

We allow users to select one of the following options in this case:  
`Use Maximum`: It will set price to Maximum Price.  
`Use Minimum`: It will set price to Minimum Price.  
`Don't Reprice`: It will not re-price.

#### When You Are Buy Box Winner: {#6}

We allow users to select one of the following options in this case:  
Decrease By Competition: Repricer will find the best price above our price so we may not lose our Buy Box and stay in a competitive price. Users can enter price and select the price to add/minus in % or $. Repricer will reprice it accordingly.  
Don't Reprice: In this case, When you are in Buy Box, Repricer will not re-price.

## Compete With Lowest Price: {#2}

We allow users to compete with Lowest offer. Users are able to add/subtract from/to Lowest price. In this rule, users may choose one option either Subtract From Lowest Price or Add To Lowest Price. Users can enter price and select the price to add/minus in % or $. According to this rule, Repricer will find the Lowest offer price and apply the strategy.  
If user sets a rule that subtract/add from/to Lowest price and apply this rule on a product and enable repricing for it. Reprice will re-price accordingly.  
What if Lowest price found less than product's minimum price or equal minimum price. In this case we allow users to set rules in the strategy.

### Scenarios:

#### When Lowest Price Below Minimum: {#7}

If Repricer found Lowest Price below your Minimum Price and user selects one of the following options.  
`Use Maximum`: It will set price to Maximum Price.

`Use Minimum`: It will set price to Minimum Price.

`Next Lowest`: Repricer will find the rating best price above your Minimum Price and add/subtract according to rule from it and sets a new price.

`Don't Reprice`:  It will not re-price.

#### When Lowest Price equals Minimum: {#8}

If  Repricer found Lowest Price equals your Minimum Price and user selects one of the following options:

`Use Maximum`: It will set price to Maximum Price.

`Use Minimum`: It will set price to Minimum Price.

`Don't Reprice`: It will not re-price.

#### If No Competition: {#9}

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

[^2]: Comment to include in footnote.

