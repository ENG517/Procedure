# Performing a Sale in Odoo POS System

## What is this for?
This article explains how to perform a sale in the Odoo POS system. At the end of this article, you’ll know how to sell a product, process payments, and record a sale in Odoo POS.

## Before you Begin
Products form the building blocks of the Odoo POS system. Ensure the following product configuration steps are completed before proceeding with a sale.

### Creating Products in Odoo
1. Launch Odoo.
2. Select **Point of Sale**.
3. Go to **Products → Products**.
4. Click **New**.
5. Go to the **General Information** tab.
6. Enter the following product details:
   - **Product Name**: The name of the product.
   - **Product Type**: The type of the product (e.g., Goods, Services, Combo).
   - **Sales Price**: The price at which the product is sold.
7. Upload an image for the product and include a product description.

### Create Product Categories
1. Go to **Point of Sale → Configuration → POS Product Categories**.
2. Click **Create**.
3. Enter a suitable name in the **Category** field.
4. Go to **Point of Sale → Products → Products**.
5. Go to the **Point of Sale** tab and fill in the **Category** field under the Point of Sale section with one or multiple POS categories.

### Make Products Available in POS
1. Go to **Point of Sale → Products → Products**.
2. Select a product.
3. Tick the **Point of Sale** checkbox at the top.

## User Roles to Choose
- Cashier  
- POS User  
- POS Manager  
- Supervisor  

## Sell a Product

### Step 1: Start a Session
1. **Launch** `Odoo`.
2. Go to **Point of Sale**.
3. Choose a store (e.g., Retail or Restaurant).
4. Click **Open Register**.
   - **Tip**: If signing in as Cashier, cash in/cash out is mandatory.  
   - **Tip**: Ensure the right store, location, and user role is selected.  
   - **Warning**: Orders cannot be created without starting a new session.

### Step 2: Add Product to Cart
1. Select product category.
2. Add the product to the cart.
3. Adjust the quantities, modifiers, and add-ons.
   - **Warning**: Ensure a product does not have $0 price before adding to the cart.

### Step 3: Review Order
1. Verify the product price, taxes applied, and quantity.
   - **Tip**: Double-check product details before proceeding to payment.

### Step 4: Process Payment
1. Click **Payment**.
2. Select payment method: Cash, Card, or Other.

### Step 5: Generate Receipt and Close Session
1. Print or email the receipt.
2. Close the order.
   - **Note**: Confirm the customer receives a copy of the receipt.  
   - **Tip**: To view customer details in the order, register the customer in the POS system.


> If the customer does not receive mail:
> - Verify you entered the correct email address.
> - Ask customer to check their spam/junk folder.
> - Enter the customer details and manually mail the receipt

## Additional Resources

- [Customer Registration](https://www.odoo.com/documentation/13.0/applications/sales/point_of_sale/overview/register.html?utm_source=chatgpt.com)
- [Odoo POS Tutorials](https://www.odoo.com/documentation/19.0/applications.html)  
- [Odoo Developer Resources](https://www.odoo.com/documentation/19.0/developer.html)  
- [Odoo POS User Docs](https://www.odoo.com/documentation/19.0/applications/sales/point_of_sale.html)  