# Performing a Sale in Odoo POS System

<!-- COMMENTS
  - All ordered steps need to be numbered, including any major or substeps.
  - Concreteness in places needs more support for a novice audience. I suggest a running example to ground the process. A grounded example can then illuminate how to proceed through conditional steps, such as any sales that would involve any combination of updating the quantities, modifiers, and/or add-ons to a sale.
  - Provide a clearer space for any prereqs, whether it's knowledge, materials, software, etc.
  - Move any alerts for steps within the context of the steo itself, rather than after the entire sequence. Also consider if the alert is actually a step or simply a note or tip.
-->

<!-- Omit this heading, since the title will do the work for you already. -->
## What is this for?
<!-- Suggestion:
Learn how to perform a sale, process a payment, and record a sale in the Odoo POS system.

I noticed that you streteched your goal statement across two sentences, so I combined them for concision. We'll work more on this prose work later, but I thought I'd note this instance.
-->
This article explains how to perform a sale in the Odoo POS system. By the end of this article, you’ll know how to sell a product, process payments, and record a sale in Odoo POS. 

## Before you Begin  

<!-- This seems like an entirely new procedure, i.e., creating a product. I'd simply add it to its own file, make sure that it is properly formatted, since many of the below bullet-point list items are sequential steps. Then, you can refer to this file as a prereq. -->

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
- Go to the **Point of Sale** tab and fill in the **Category** field under the **Point of Sale** section with one or multiple POS categories.  

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
<!-- Suggestion:
  - Delete "## How to Sell a Product?", since it's already known via the title.
  - Revise the H3 headings to H2
-->
## How to Sell a Product?

<!-- Remove "Step" throughout, since it is implied. -->
### Step 1: Start a POS Session

<!-- Comments:
  - These are all sequential steps, so use numbered list items. Change throughout.
-->
- Launch **Odoo**.  <!-- This step is implied, so perhaps omit.-->
<!-- Suggestion:
1. On the initial screen, select  **Point of Sale**.

or

1. To start a new POS session, select **Point of Sale**.

    ![Enter helpful screenshot here with emphasizes area](./path/to/img.png)

    > Figure x. Meaningful caption here.

- Notice how these variations orient the user to where they should begin. I think you should include more screenshots if possible. If not, provide orientation descriptions. We'll cover those details of writing later, but we learned that steps should provide that information, when pertinent.
-->
- Go to **Point of Sale**.
<!-- This is a conditional step, which you could guide the novice user through. -->
- Choose a store.  
  - Example: Retail or Restaurant.  
- Click **Open Register**.  

<!-- Not sure what this means, since the heading suggests that this is the process itself. So, is it a warning? Or is it a staging sentence after the heading? -->
⚠️ **Warning:** Orders cannot be created without starting a new session.  

### Step 2: Add Product to Cart
- Select product category.  
- Add the product to the cart.  

  ![Add Items to Cart](./assets/images/Items%20in%20cart.jpeg)

    *Fig 2. Add Items in Cart*
  <!-- Added this warning here, under the appropriate step. -->
  ⚠️ **Warning:** Ensure a product does not have $0 price before adding to the cart.

- Adjust the quantities, modifiers, and add-ons.
  <!-- While you mau -->

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

Find my procedure [here](./assets/docs/Procedure.pdf)

