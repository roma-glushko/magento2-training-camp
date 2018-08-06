# Magento2 Training Camp

Magento 2 Solution Specialist Training Camp is a study programm that helps you to get familiar with Magento 2 platform 
via tasks, use cases, user stories.

## Store Setup (STS)

### Store Structure (Website/Store/Store View)

#### STS-SS-1. Case

Merchant wants to sell kitchen cabinets inside U.S. only. What optimal/simplest store structure would you suggest him?

#### STS-SS-2. Case 

Merchant from Germany wants to sell builing materials inside the country and to his customers in Italy. What optimal/simplest store structure would you suggest him?

#### STS-SS-3. Case

Merchant has two main branches of products: pets and pet's equipments. He wants to sell them on different domains which is more convinient for his marketing strategy. Both product branches would sell in France. What optimal/simplest store structure would you suggest him?

#### STS-SS-4. Case

Merchant sells beding products to Germany, France and U.K. What optimal/simplest store structure would you suggest him?

### Store Configurations

#### STS-SC-1. Case

Merchant from Florida wants to see admin panel in his local time.

## Catalog (CAT)

### Categories

#### CAT-CT-1. Case 

The merchant wants to add two categories to the store.
First one is `Computer Mouse` and the second one is `Computer Keyboard`.
These categories should be showing on the storefront with `computer-mouse` and `computer-keyboard` URLs.
The `Computer Mouse` category should contain one product with computer mouse parameters (name, SKU, image, short description, description ...).
The `Computer Keyboard` should contain two products with computer keyboard params (name, SKU, image, short description, description ...).
The merchant wants to see the store portfolio (screenshots and descriptions from storefront).

#### CAT-CT-2. Task

Create a category "Woman Clothes" that will show content of CMS block instead of product list.

#### CAT-CT-3. Task

Create a category "Cart Parts" with three subcategories: "Volvo", "BMW", "Mercedes".

#### CAT-CT-4. Task

Create a "Music" category and specify information for search engines. Make sure information is on the frontend page.

#### CAT-CT-5. Case

Merchant needs to create a menu on the store with three sections: "Office chairs", "High chairs" and "Armchairs". Under all of them, 1 product will be sold.

### Products

#### CAT-PR-1. TASK

Create a simple product "Black Leather chair" with SKU "BLK-LTHR-CHR02" and an image attached.

#### CAT-PR-2. Case

Merchant wants to sell t-shirts. Each t-shirt has black and white color variations, three different sizes (S, M, L). Can you please create a couple of products as an example of how that can be configured with Magento.

## Sales (SAL)


### Orders

#### SAL-OR-1. Task

Create order from the admin panel.

#### SAL-OR-2. Task



### Shipments

TBD

### Invoices

TBD

### Credit Memo

TBD

## Checkout (CO)

### CO-1. Task

Buy a product on the store as visitor.

### CO-2. Task

Buy a product on the store as customer.

### CO-3. Task

Configure the PayPal payment method with sandbox mode. 
Create paypal account and provide all needed data to Magento configurations.
Create order via PayPal payment method.
Interest links: https://devdocs.magento.com/guides/v2.2/cloud/live/paypal-onboarding.html
https://mage2.pro/t/topic/1083

### CO-4. Task

Merchant wants to configure the free shipping for testing checkout.
Also, he wants to configure the Free Shipping method name to *Free Shipping TEST DO NOT USE*.
Provide the test orders screenshots.

### CO-5. Task

Merchant wants to use the Table Rates shipping method for using only for United States country.
Create test orders and provide the screenshots.

### CO-6. Task

Create the order and reorder it via customer account.

## Customer (CST)

### CST-1. Task

Register in the store as a customer.

### CST-2. Task

Create a customer from Magento Admin. Specify the default billing and shipping addresses.

### CST-3. Task

Add a befault billing and shipping address for registred customer.

## Marketing (MRK)

### Cart Price Rules

#### MRK-CR-1.

Merchant wants to configure a free shipping for orders that contains only products from "Samples" category.

#### MRK-CR-2.

Merchant wants create the 25% discount for orders that has grand total more than 1000$.

#### MRK-CR-3.

Create the two products:
1. Product *Mac Book Air 2017* from *Laptops* category
2. Product *Mac Book Cover Black* from *Laptop Accessories*
Merchant wants to create the cart price rule to get free *Mac Book Cover Black* when you add the *Mac Book Air 2017* to cart.

#### MRK-CR-4.

Merchant wants to create coupon code "K111198K" for getting 50% discount.

#### MRK-CR-5.

Merchant wants to generate 50 couponts with 15% discount.

#### MRK-CR-6

Merchant wants configure the cart price rule to get one free plate when you added 5 plates to cart.

### Catalog Price Rules

TBD

## Content (CNT)

### CMS pages/CMS blocks

#### CNT-PB-1. Task

Create a CMS page with name "About Us". 

#### CNT-PB-2. Case

Marchant wants to have a static page where information about his shipping policy described to the customers.

#### CNT-PB-3. Case

Merchant looks into a way of managing the same block of information about promotions on "Diving Tools" category and "Diving is Fun" page.

#### CNT-PB-4. Case

Marchant wants to have a place on the store where will be rendered a information for search engines: 

"Check out our extensive range of chairs, seats & stools. Find inspiration and ideas for your home at YOURCHAIR.COM today." 

## System (SYS)

### System Data Transfer

#### SYS-DT-1

Export all products from the store.

#### SYS-DT-2

Import "Mac Book Pro 2015" product to "Laptop" category.

#### SYS-DT-3

Export products from "Laptop" category with stock status = "Out of stock".

#### SYS-DT-4

Export Customer Addresses only from US.

## E-Commerce (ECM)

### ECM-1. Question

What's drop-shipping? 

### ECM-2. Question

What is it "Omnichannel" and "Multichannel"? What's difference between those strategies? 

### ECM-3. Question

What is it Google Analytics? What's a purpose using it on the website? Which kind of information can be analized?

### ECM-4. Question

What is "SEO"? Why it's important for e-commerce? 
What is search engine? Abstract architecture of search engines, main components.
What do you know about meta tags?
Describe please duplicated page content issue. How to fix it?

### ECM-5. Question

What is "faceted search"? Does Magento support it? How to enable it if so?

### ECM-6. Question

What is "faceted search"? Does Magento support it? How to enable it if so?

### ECM-7. Question

What's "hosting"? Compare popular Magento hostings: MageMojo, Nexcess, Magento Cloud, AWS

### ECM-8. Question



## Magento Architecture (MGA)

### MGA-1. Question 

What is it Magento Cache?
