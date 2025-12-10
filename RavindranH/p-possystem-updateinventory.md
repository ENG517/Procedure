# Managing Inventory in Odoo POS System

This article explains how to manage inventory in the Odoo POS system. 
Updating product details in the inventory is referred to as making an inventory adjustment in the Odoo POS terminology. 
Throughout this article you may come across varied terminologies like "registering a product", or "updating a product", or "saving a product", and they all mean that you're adjusting the inventory. 

## Prerequisites
Before updating inventory, ensure the following:

- You are logged in to the latest version of the Odoo POS application on your Android, iOS, or Windows device.
- You have permission to view and manage inventory.
- Your physical inventory matches the products created in Odoo POS.

## Product Requirements

- Create a product in Odoo POS for every item in your physical stock. 
  **Warning:** If a product is not created, it cannot be sold at the POS system.  
  **Example:** If you have Bacon Burger in stock but did not register it in the inventory, the item will not appear on the order screen.

- Enter accurate product details such as price, tax, category, and quantity.  
  **Warning:** Incorrect prices or tax settings may cause customer overcharging or accounting errors.  
  **Example:** Setting a $12 sandwich to $8 or applying 0% tax instead of 7% creates incorrect sales reports.

- Select the *Point of Sale* checkbox when creating products to make them available for sale.  
  **Warning:** If this box is not selected, the product will remain invisible on the POS order screen.

---

## 1. Access the Inventory Module

1.1 Select **Inventory** from the Odoo dashboard.  

![Inventory](./assets/images/screenshots/Figure13.jpeg)
*Figure 1: Odoo dashboard showing the Inventory Module.*

---

## 2. Create Inventory Adjustment

2.1 Navigate to **Operations → Physical Inventory → Adjustments → Physical Inventory**.  
**Note:** If this is your first inventory adjustment, the inventory list may appear empty until item quantities are entered.

![Adjustments](./assets/images/screenshots/Figure%2014.jpeg)

*Figure 2: The Inventory Adjustments option displayed under Operations.*

---

## 3. Set Product Quantities in Inventory

3.1 Click **New**.

3.2 Under **Product**, select the item you want to register in the inventory.  
**Note:** If no products appear, create them in the POS system first.
Refer to [Products Creation](https://www.odoo.com/documentation/19.0/applications/websites/ecommerce/products.html) for detailed information on how to create products in the Odoo POS system. 


3.3 In the **Counted Quantity** field, enter the exact physical stock count.  
**Example:** Enter **6** if you have 6 Bacon Burgers.  

**Important:** Counted Quantity must match your actual physical stock.

3.4  Click **Apply** on the far right to save the adjustment.

---

## 4. Review the Adjustment

4.1  Check the **Counted Quantity**, **On-Hand Quantity**, and **Difference** fields:

- **Green:** Counted quantity is higher than on-hand.  
  *Example:* On-hand 4, counted 6 → **+2** (green).

- **Red:** Counted quantity is lower than on-hand.  
  *Example:* On-hand 10, counted 7 → **–3** (red).

- **Blank:** Quantities match.  
  *Example:* On-hand 12, counted 12 → *(no difference)*.

**Note:** This step confirms that the physical count matches the system record, preventing stock errors and discrepancies.

---

## 5. View the Adjustment History

5.1  Click **History** to view previous inventory adjustments.  
- The user who performed the count appears in parentheses in the **Reference** field.  
- The user who applied the adjustment appears under **Done By**.

**Note:** Offline POS devices cache inventory adjustments and sync them when reconnected.  
**Warning:** If syncing fails, stock levels may become inaccurate.  
**Example:** If you mark an item as 0 units while offline, POS may still show 3 units until sync completes.

---

## Additional Resources
Refer to [Inventory Adjustments](https://www.odoo.com/documentation/19.0/applications/inventory_and_mrp/inventory/warehouses_storage/inventory_management/count_products.html?highlight=inventory) for more information on matching warehouse inventory counts and avoiding discrepancies.

Find my procedure [here](./assets/docs/Procedure%20Final.pdf)