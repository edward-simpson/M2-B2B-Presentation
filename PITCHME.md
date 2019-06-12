---?color=linear-gradient(to right, #c02425, #f0cb35)
@title[Introduction]

# Magento 2 B2B

---
@title[What is it?]

# What is it?

---

* Commerce module
* Simpifying business to business sales

---

### Modules

* 19 different modules
    * Company
    * Shared Catalog
    * Negotiable Quotes
    * Requisition lists
    * Quick order

+++

#### B2b

Makes up the base module, provides some branding elements

+++

#### Company

* Company
Allows seller to **<span style="color: #ff9696">create a company account</span>**, and **<span style="color: #ff9696">assign members of the company (*customer accounts*)</span>** to company account

* CompanyCredit
**<span style="color: #ff9696">New payment method</span>** akin to store credit

* CompanyPayment
Allows specific **<span style="color: #ff9696">payment methods</span>** to be **<span style="color: #ff9696">enabled/disabled</span>** **<span style="color: #ff9696">PER</span>** B2B company

+++

#### Shared Catalog

* SharedCatalog
* BundleSharedCatalog
* ConfigurableSharedCatalog
* GiftCardSharedCatalog
* GroupedSharedCatalog

Defines the **<span style="color: #ff9696">visibility</span>** of **<span style="color: #ff9696">products and prices</span>** in the **<span style="color: #ff9696">catalog</span>** and **<span style="color: #ff9696">B2B Quotes**
for **<span style="color: #ff9696">different company accounts**


+++

#### Negotiable Quote

* NegotiableQuote
* NegotiableQuoteSharedCatalog
* BundleNegotiableQuote
* ConfigurableNegotiableQuote
* GiftCardNegotiableQuote

Allows buyer and seller to **<span style="color: #ff9696">generate a quote</span>**, and **<span style="color: #ff9696">negotiate product and/or shipping prices</span>** before order gets placed

+++

#### Requisition List

* RequisitionList
* BundleRequisitionList
* ConfigurableRequisitionList
* GiftCardRequisitionList

Allows buyer to **<span style="color: #ff9696">create multiple lists of products</span>** (a-la wishlist), to use in order placement

+++

#### Quick Order
* QuickOrder

Allows buyer to **<span style="color: #ff9696">generate orders</span>** based on either **<span style="color: #ff9696">entering SKU</span>**, or **<span style="color: #ff9696">uploading SKU CSV file</span>**

---


# FIN

<style>
#fin {
    -webkit-transform-style: preserve-3d;
    -webkit-animation: spin 3s infinite ease-out;
    animation: spin 3s infinite;
}

@-webkit-keyframes spin {
  0% {-webkit-transform: rotateX(-20deg) rotateY(20deg);}
  100% {-webkit-transform: rotateX(-20deg) rotateY(740deg);}
}

@keyframes spin {
  0% {-webkit-transform: rotateX(-20deg) rotateY(20deg);}
  100% {-webkit-transform: rotateX(-20deg) rotateY(740deg);}
}
</style>

---

* Tiered customers/buyer
* Specific roles and permissions within parent company
* Track quotes
* Detailed order histories
* Online credit management/Pay on credit

---
### Customisations for B2B customers
* Catalogues
* Price lists
* Payment options

---
### Order management
#### Quoting
Buyer can:
* Add items to cart
* Request quote using cart items
* Assign description (e.g. Please can I have a discount)
* Assign identifier/name to quote

---

Seller can:
* View:
   * Quote summary
   * Company information
   * Contract price
* Customise:
    * Discount
    * Contents (items, quantity)
    * Add expiration date
* Discount quote based on:
    * Percentage
    * Flat amount
    * Propose new flat price
* Possible to automate based on set rules
* Submit quote back to buyer, which they can convert into order 

---

##### Order by
* SKU
* Uploading CSV
* Choosing items from pre-set lists
