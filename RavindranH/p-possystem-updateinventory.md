 # Procedure: Manually Updating Inventory in a POS System

## Device Requirements
- **POS Terminal/Workstation**: Touchscreen or desktop PC with inventory management module installed  
- **Barcode Scanner**: OPOS-compliant, used to quickly identify items when updating stock  
- **Receipt/Label Printer (Optional)**: For printing updated stock labels or inventory adjustment slips  
- **Cash Drawer (Not Required)**: Inventory updates do not require a cash drawer connection  
- **External Storage/Export Device (Optional)**: USB drive or secure network path for exporting updated inventory data  
- **Internet Connection**: Required for cloud-based inventory synchronization across multiple outlets  

---

## System Requirements
- POS workstation with:
  - Windows 10 or later (or supported OS based on vendor)  
  - Minimum 8GB RAM, 256GB SSD, dual-core processor  
  - Barcode scanner and printer drivers compliant with OPOS standards  
- POS software with **Inventory Management Module** enabled  
- Database access with real-time stock tracking capability  
- User account with **Manager** or **Inventory Supervisor** role permissions  

---

## Prerequisites
- User has login credentials with access to the **Inventory Management** module  
- Inventory catalog is already set up with product codes, barcodes, and categories  
- Current stock levels are available (from previous sales or inventory imports)  
- If physical stock-taking is performed, a count sheet should be ready before updating  
- Backup of inventory database recommended before making manual adjustments  

---

## Step-by-Step Procedure
1. **Login to POS System**  
   - Enter *Manager/Inventory Supervisor* credentials.  
   - Navigate to the **Back Office → Inventory Management** module.  

2. **Search for Product(s)**  
   - Use barcode scanner to scan item code OR  
   - Search by product name, SKU, or category.  

3. **Select Item for Update**  
   - Open the product details screen.  
   - Verify existing stock levels shown in the system.  

4. **Update Inventory Quantities**  
   - Choose **Adjust Stock / Manual Update** option.  
   - Enter the **new stock quantity** (e.g., after delivery, corrections, or returns).  
   - Specify reason for adjustment (e.g., “New Stock Received,” “Damaged Goods Removed,” “Stock Correction”).  

5. **Save Changes**  
   - Confirm update and save.  
   - System logs the adjustment with timestamp, user ID, and reason.  

6. **(Optional) Print Updated Labels or Adjustment Report**  
   - Print shelf labels if pricing or barcodes changed.  
   - Print adjustment slip for auditing and stockroom records.  

7. **Verify Updated Inventory**  
   - Refresh stock list to confirm updated levels.  
   - Cross-check with physical stock count if necessary.  

---

## Notes
- Manual inventory updates should be logged with clear reasons to ensure **audit compliance**.  
- For bulk updates, use import functionality (CSV/Excel) if supported instead of individual updates.  
- Inventory adjustments directly affect **stock availability and sales reports** — always double-check entries.  
- Barcode scanners reduce errors when selecting items for update. 
- For cloud-based POS, ensure system syncs successfully to prevent discrepancies across outlets.  

---

## References – OPOS Documentation
- OPOS ensures barcode scanners, printers, and other retail devices integrate smoothly with POS systems.  

Key resources:  
- [OPOS Common Control Objects Download](https://www.microsoft.com/en-us/download/details.aspx?id=42095)  
- [UnifiedPOS (UPOS) Specification – CCO](https://www.omg.org/upos/)  
- [OPOS Developer Resources](https://www.posforsystem.com/opos/)  