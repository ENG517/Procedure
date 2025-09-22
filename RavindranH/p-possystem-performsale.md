# Performing a Sale in Odoo POS System

## What is this for?
This article explains how to perform a sale in the Odoo POS system. At the end of this article, you’ll know how to sell a product, process payments, and record a sale in Odoo POS.

## Before you Begin
- Products form the building blocks of the Odoo POS system. 
- Ensure the following product configuration steps are completed before proceeding with a sale.

### Creating Products in Odoo
- Launch **Odoo**.
- Select **Point of Sale**
- Go to **Products → Products**
- Click **New**
- Go to the **General Information** tab.
- Enter the following product details:
   - **Product Name**: The name of the product
   - **Product Type**: The type of the product (e.g., Goods, Services, Combo)
   - **Sales Price**: The price at which the product is sold
- Upload an image for the product and include a product description.

### Creating Product Categories
- Go to **Point of Sale → Configuration → POS Product Categories**.
- Click **Create**.
- Enter a suitable name in the **Category** field.
- Go to **Point of Sale → Products → Products**.
- Go to the **Point of Sale** tab and fill in the **Category** field under the Point of Sale section with one or multiple POS categories.

### Making Products Available in POS
- Go to **Point of Sale → Products → Products**.
- Select a product.
- Tick the **Point of Sale** checkbox at the top.

## User with Access Permissions

- Cashier  
- POS User  
- POS Manager  
- Supervisor  

## Sell a Product

### Step 1: Start a Session
- Launch **Odoo**.
- Go to **Point of Sale**.
- Choose a store (e.g., Retail or Restaurant).
- Click **Open Register**.
   - **Tip**: If signing in as Cashier, cash in/cash out is mandatory.  
   - **Note**: Ensure the right store, location, and user role is selected.  
   - **Warning**: Orders cannot be created without starting a new session.

### Step 2: Add Product to Cart
- Select product category.
- Add the product to the cart.
- Adjust the quantities, modifiers, and add-ons.
   - **Warning**: Ensure a product does not have $0 price before adding to the cart.
   - **Tip**: You can also add a product to cart by scanning its barcode.

### Step 3: Review Order
- Verify the product price, taxes applied, and quantity.
   - **Tip**: Double-check product details before proceeding to payment.

### Step 4: Process Payment
- Click **Payment**.
- Select payment method: Cash, Card, or Other.

### Step 5: Generate Receipt and Close Session
- Print or email the receipt.
- Close the order.
   - **Note**: Confirm the customer receives a copy of the receipt.  
   - **Tip**: To view customer details in the order, register the customer in the POS system.


> If the customer does not receive a copy of the receipt:
> - Verify you entered the correct email address.
> - Ask customer to check their spam/junk folder.
> - Enter the customer details and manually mail the receipt

## Additional Resources

- [Customer Registration](https://www.odoo.com/documentation/13.0/applications/sales/point_of_sale/overview/register.html?utm_source=chatgpt.com)
- [Odoo POS Tutorials](https://www.odoo.com/documentation/19.0/applications.html)  
- [Odoo Developer Resources](https://www.odoo.com/documentation/19.0/developer.html)  
- [Odoo POS User Docs](https://www.odoo.com/documentation/19.0/applications/sales/point_of_sale.html)  