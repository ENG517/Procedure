# Performing a Sale in Odoo POS System

## What is this for?
This article explains how to perform a sale in the Odoo POS system. By the end of this article, you’ll know how to sell a product, process payments, and record a sale in Odoo POS. 

## Before you Begin  

Ensure the following product configuration steps are completed before proceeding with a sale:

### Create Products in Odoo
- Launch **Odoo**.  
- Click **Point of Sale**.  

![POS MODULE](./assets/images/POS%20Module.jpeg)

*Fig 1. Select POS Module*
- Go to **Products → Products**.  
- Select **New**.  
- Go to the **General Information** tab.  
- Enter the following product details:  
  - **Product Name** - The name of the product.  
  - **Product Type** - The type of the product (e.g., Goods, Services, Combo).  
  - **Sales Price** - The price at which the product is sold.  
- Upload an image for the product and include a product description.  

### Create Product Categories
- Go to **Point of Sale → Configuration → POS Product Categories**.  
- Click **Create**.  
- Enter a suitable name in the **Category** field.  
- Go to **Point of Sale → Products → Products**.  
- Go to the **Point of Sale** tab and fill in the **Category** field under the Point of Sale section with one or multiple POS categories.  

### Make Products Available in POS
- Go to **Point of Sale → Products → Products**.  
- Select a product.  
- Tick the **Point of Sale** checkbox at the top.  

### User Roles with Access Permissions
- **Cashier**  
- **POS User**  
- **POS Manager**  
- **Supervisor**  

---

## How to Sell a Product?

### Step 1: Start a POS Session

- Launch **Odoo**.  
- Go to **Point of Sale**.  
- Choose a store.  
  - Example: Retail or Restaurant.  
- Click **Open Register**.  

⚠️ **Warning:** Orders cannot be created without starting a new session.  

### Step 2: Add Product to Cart
- Select product category.  
- Add the product to the cart.  

![Add Items to Cart](./assets/images/Items%20in%20cart.jpeg)

*Fig 2. Add Items in Cart*  

- Adjust the quantities, modifiers, and add-ons.  

⚠️ **Warning:** Ensure a product does not have $0 price before adding to the cart.  

### Step 3: Review Order
- Verify the product price, taxes applied, and quantity.  

💡 **Tip:** Double-check product details before proceeding to payment.  

### Step 4: Complete the Payment
- Click **Payment**.  
- Select payment method: **Cash, Card, or Other**.  
- Click **Validate** after choosing the payment method. The order is complete.  

![Payment Sucess](./assets/images/Payment%20Success.jpeg)

*Fig 3. Payment Success*  

- Click **New Order**, if willling to proceed with another order.  
📌 **Note:** It is recommended to print receipt before creating a new order. 

### Step 5: Generate Receipt and Close Session
- Print or email the receipt.  
- Close the order.  

📌 **Note:** Confirm the customer receives a copy of the receipt.  

---
## Additional Resources
- [Odoo POS Product Configuration](https://www.odoo.com/documentation/19.0/applications/sales/point_of_sale/configuration.html)
- [Odoo POS Tutorials](https://www.odoo.com/slides/point-of-sale-28)
- [Odoo POS User Docs](https://www.odoo.com/documentation/19.0/applications/sales/point_of_sale.html)
- [Odoo POS Support](https://www.odoo.com/help)

