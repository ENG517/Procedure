# Performing a Sale in Odoo POS System
This article teaches you how to perform a sale and process payments in the Odoo POS system.

##Prerequisites

Before you proceed to perform a sale, make sure:

- You are logged into the latest version of the Odoo application on an Android, iOS, or Windows device.
- You have the necessary user permissions to perform sales and handle payments.
- The products you want to sell are created and available in the POS system.  


---

## 1. Start a POS Session

### 1.1 Click **New Session** to activate your POS session.

> **Note:** You can log in from different user accounts, but you can open only one session per browser.

---

## 2. Choose Your Store

### 2.1 Click **Point of Sale** from the Odoo dashboard.

![Figure 1. Odoo dashboard showing the POS application](Figure 1.jpeg)

### 2.2 Review the list of stores displayed on the screen.

> **Note:** Each store functions as a separate business unit in the POS system.

*Figure 2. List of stores displayed in the POS application*
![Figure2. List of stores disolayed in the POS application](./assets/images/Figure 2.jpeg)

### 2.3 Select the store where you will make the sale. **Example:** Select **Restaurant** if that is where you work.

---

## 3. Set Up Cash Register at the Store

### 3.1 Click **Open Register** for the selected store.

![Figure 3. The Open Register option displayed in the selected store] (./assets/images/Figure 3.jpeg)


### 3.2 Once inside the store, click the Money icon in the Opening Control window.

### 3.3 Enter the number of notes and coins you have. **Example:** Enter **10** under **$200** for ten 200-dollar notes and **10** under **$1** for ten 1-dollar coins.

![Figure 4. The Coins/Notes pop-up where the opening cash amount is configured] (./assets/images/Figure 4.jpeg)

### 3.4 Click **Confirm** to save the amount.

> **Tip:** Always verify your opening cash carefully so end-of-day calculations stay accurate.

### 3.5 Click **Open Register** again to complete the register setup.

---

## 4. Start a New Order

### 4.1 Click **New Order**.

> **Note:** *Dine-In* is selected by default. Tap **Dine-In** to switch to *Takeaway* if the customer prefers.

### 4.2 Select a product category to view its items.

**Example:** Select **Foods** to view all food items.

![Figure 5. The order screen displaying product categories and products] (./assets/images/Figure 5.jpeg)


### 4.3 Scroll through the order screen to select the item you want.

> **Note:** If you do not see the item on the screen, click **Search Products** at the top.

### 4.4 Select the item the customer wants to order.

**Example:** Bacon Burger.  
If sides or add-ons are available, a pop-up appears.

![Figure 6. The sides/add-ons pop-up appearing when the product is selected] (./assets/images/Figure 6.jpeg)


### 4.5 Select the sides or add-ons.

**Example:** Fries.

### 4.6 Click **Add**.  


![Figure 7. The Bacon Burger with Fries appears in the cart] (./assets/images/Figure7.jpeg)

---

### Optional Steps

### 4.7 To change quantity, select the item in the cart.

### 4.8 Click **Qty** and enter the new quantity using the keypad.

**Example:** Increase the quantity from 1 to 2 if the customer wants two bacon burgers.

### 4.9 Click **Price** and enter a custom price if required.

> **Warning:** Item price cannot be zero or negative.

---

## 5. Add a Customer

### 5.1 Click **Customer** in the keypad area.

> **Tip:** If it is a returning customer, their name may appear automatically.

### 5.2 Click **Create** to add a new customer.

> **Tip:** You can update or delete existing customer details if needed.

*Figure 8. The pop-up where customer information can be added*

![Figure 8. The pop-up where customer information can be added] (./assets/images/Figure8.jpeg)


### 5.3 Enter the customer details.

### 5.4 Click **Save**.  
The customer’s name appears in the cart.  
**Example:** Brandon Freeman.

---

## 6. Complete the Payment

### 6.1 Click **Payment**.

![Figure 9. Payment methods displayed along with the order total] (./assets/images/Figure9.jpeg)


### 6.2 Select the customer’s preferred payment method.

**Example:** Choose **Cash** if the customer wants to pay with cash.

> **Tip:** The system automatically supports split payments.

### 6.3 Enter the amount the customer wants to pay.

**Example:**  
If the total is **$21** and the customer pays **$10** in cash and **$11** by card:

- Enter **10** under **Cash** — the remaining balance appears.
- Select **Card** and enter **11**.

### 6.4 Click **Validate**.  
The system confirms the payment and displays the invoice.

![Figure 10.Payment successful alert after completing the payment ] (./assets/images/Figure10.jpeg)


---

## 7. Print or Send the Receipt

### 7.1 Click **Print Full Receipt** to print the invoice.

### 7.2 For a digital copy, enter the customer’s email address or let them scan the QR code.

### 7.3 If this is your last order of the day, click **Close Register**.

---

## Additional Resources

Refer to POS tutorials for more information on:

- Product creation  
- Invoicing  
- Cash handling in the Odoo POS system



























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

